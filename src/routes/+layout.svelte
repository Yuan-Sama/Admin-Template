<script>
	import 'bootstrap-icons/font/bootstrap-icons.min.css';
	import '../app.css';
	import LogoImage from '$assets/logo.png';
	import ProfileImage from '$assets/profile.jpg';
	import Badge from '$components/Badge.svelte';
	import DropdownMenu from '$components/DropdownMenu.svelte';
	let { children } = $props();

	const SidebarMenu = $state([
		{ link: '/', title: 'Dashboard', biIconClass: 'bi bi-grid' },
		{
			title: 'Components',
			biIconClass: 'bi bi-menu-button-wide',
			/** @type {import("svelte").SvelteComponent<{ class?: string; collapseAtStart?: boolean; children: import("svelte").Snippet; }, any, any> & { show: () => void; hide: () => void; showing: () => boolean; } & { $$bindings: ""; } | undefined} */
			refThis: undefined,
			subMenu: [
				{ link: '/components/alerts', title: 'Alerts' },
				{ link: '/components/accordion', title: 'Accordion' },
				{ link: '/components/badges', title: 'Badges' },
				{ link: '/components/breadcrumbs', title: 'Breadcrumbs' },
				{ link: '/components/buttons', title: 'Buttons' },
				{ link: '/components/cards', title: 'Cards' },
				{ link: '/components/carousel', title: 'Carousel' },
				{ link: '/components/list-group', title: 'List group' },
				{ link: '/components/modal', title: 'Modal' },
				{ link: '/components/tabs', title: 'Tabs' },
				{ link: '/components/pagination', title: 'Pagination' },
				{ link: '/components/progress', title: 'Progress' },
				{ link: '/components/progress', title: 'Progress' },
				{ link: '/components/spinners', title: 'Spinners' },
				{ link: '/components/tooltips', title: 'Tooltips' }
			]
		},
		{
			title: 'Forms',
			biIconClass: 'bi bi-journal-text',
			/** @type {import("svelte").SvelteComponent<{ class?: string; collapseAtStart?: boolean; children: import("svelte").Snippet; }, any, any> & { show: () => void; hide: () => void; showing: () => boolean; } & { $$bindings: ""; } | undefined} */
			refThis: undefined,
			subMenu: [
				{ link: '/forms/elements', title: 'Elements' },
				{ link: '/forms/layouts', title: 'Layouts' },
				{ link: '/forms/editors', title: 'Editors' },
				{ link: '/forms/validation', title: 'Validation' }
			]
		},
		{
			title: 'Tables',
			biIconClass: 'bi bi-layout-text-window-reverse',
			/** @type {import("svelte").SvelteComponent<{ class?: string; collapseAtStart?: boolean; children: import("svelte").Snippet; }, any, any> & { show: () => void; hide: () => void; showing: () => boolean; } & { $$bindings: ""; } | undefined} */
			refThis: undefined,
			subMenu: [
				{ link: '/tables/general', title: 'General Tables' },
				{ link: '/tables/data', title: 'Data Tables' }
			]
		},
		{
			title: 'Charts',
			biIconClass: 'bi bi-bar-chart',
			/** @type {import("svelte").SvelteComponent<{ class?: string; collapseAtStart?: boolean; children: import("svelte").Snippet; }, any, any> & { show: () => void; hide: () => void; showing: () => boolean; } & { $$bindings: ""; } | undefined} */
			refThis: undefined,
			subMenu: [
				{ link: '/charts/chartjs', title: 'Chart.js' },
				{ link: '/charts/apexcharts', title: 'ApexCharts' },
				{ link: '/charts/echarts', title: 'ECharts' }
			]
		},
		{ title: 'Pages' },
		{ link: '/pages/users-profile', title: 'Profile', biIconClass: 'bi bi-person' },
		{ link: '/pages/faq', title: 'F.A.Q', biIconClass: 'bi bi-question-circle' },
		{ link: '/pages/contact', title: 'Contact', biIconClass: 'bi bi-envelope' },
		{ link: '/pages/register', title: 'Register', biIconClass: 'bi bi-card-list' },
		{ link: '/pages/login', title: 'Login', biIconClass: 'bi bi-box-arrow-in-right' },
		{ link: '/pages/error-404', title: 'Error 404', biIconClass: 'bi bi-dash-circle' },
		{ link: '/pages/blank', title: 'Blank', biIconClass: 'bi bi-file-earmark' }
	]);
</script>

<svelte:head>
	<title>Admin Tailwindcss Template</title>
</svelte:head>

<header
	class="fixed left-0 right-0 top-0 z-[1030] flex h-[60px] items-center bg-white pl-5 shadow-[0px_2px_20px_rgba(1,41,112,0.1)]"
>
	<div class="flex items-center justify-between">
		<a href="/" class="flex items-center xl:w-72">
			<img class="mr-[6px] max-h-[26px]" src={LogoImage} alt="Logo" />
			<span
				class="hidden font-['Nunito',_sans-serif] text-[26px] font-bold leading-[1] text-[#012970] lg:block"
				>Admin Template</span
			>
		</a>
		<i class="bi bi-list cursor-pointer pl-[10px] text-[32px] text-[#012970]"></i>
	</div>
	<!-- End Logo -->

	<div class="min-w-[360px] px-5">
		<form class="flex w-full items-center" action="#">
			<input
				class="w-full rounded-[3px] border border-solid border-[rgba(1,_41,_112,_0.2)] py-[7px] pl-[8px] pr-[38px] text-sm text-[#012970] duration-300 focus:border-[rgba(1,_41,_112,_0.3)] focus:shadow-[0_0_10px_0_rgba(1,_41,_112,_0.15)] focus:outline-0"
				type="text"
				name="query"
				placeholder="Search"
				title="Enter search keyword"
			/>
			<button class="-ml-[30px] text-[#012970]" type="submit" title="Search" aria-label="Search">
				<i class="bi bi-search"></i>
			</button>
		</form>
	</div>
	<!-- End Search Bar -->

	<nav class="ml-auto">
		<ul class="flex items-center">
			<li class="mb-[5px] block lg:hidden">
				<button class="nav-lik nav-icon search-bar-toggle" aria-label=" ">
					<i class="bi bi-search"></i>
				</button>
			</li>
			<!-- End Search Icon-->

			<li class="relative">
				<button class="relative mr-[25px] text-2xl text-[#012970]">
					<i class="bi bi-bell"></i>
					<Badge
						class="absolute inset-[-5px_-6px_auto_auto] bg-[rgb(13,110,253)] px-[6px] py-[3px] font-normal"
					>
						4
					</Badge>
				</button><!-- End Notification Icon -->

				<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow notifications hidden">
					<li class="dropdown-header">
						You have 4 new notifications
						<a href={'#'}><span class="badge rounded-pill bg-primary ms-2 p-2">View all</span></a>
					</li>
					<li>
						<hr class="dropdown-divider" />
					</li>

					<li class="notification-item">
						<i class="bi bi-exclamation-circle text-warning"></i>
						<div>
							<h4>Lorem Ipsum</h4>
							<p>Quae dolorem earum veritatis oditseno</p>
							<p>30 min. ago</p>
						</div>
					</li>

					<li>
						<hr class="dropdown-divider" />
					</li>

					<li class="notification-item">
						<i class="bi bi-x-circle text-danger"></i>
						<div>
							<h4>Atque rerum nesciunt</h4>
							<p>Quae dolorem earum veritatis oditseno</p>
							<p>1 hr. ago</p>
						</div>
					</li>

					<li>
						<hr class="dropdown-divider" />
					</li>

					<li class="notification-item">
						<i class="bi bi-check-circle text-success"></i>
						<div>
							<h4>Sit rerum fuga</h4>
							<p>Quae dolorem earum veritatis oditseno</p>
							<p>2 hrs. ago</p>
						</div>
					</li>

					<li>
						<hr class="dropdown-divider" />
					</li>

					<li class="notification-item">
						<i class="bi bi-info-circle text-primary"></i>
						<div>
							<h4>Dicta reprehenderit</h4>
							<p>Quae dolorem earum veritatis oditseno</p>
							<p>4 hrs. ago</p>
						</div>
					</li>

					<li>
						<hr class="dropdown-divider" />
					</li>
					<li class="dropdown-footer">
						<a href={'#'}>Show all notifications</a>
					</li>
				</ul>
				<!-- End Notification Dropdown Items -->
			</li>
			<!-- End Notification Nav -->

			<li class="relative">
				<button class="relative mr-[25px] text-2xl text-[#012970]">
					<i class="bi bi-chat-left-text"></i>
					<Badge
						class="absolute inset-[-5px_-6px_auto_auto] bg-[rgb(25,135,84)] px-[6px] py-[3px] font-normal"
					>
						3
					</Badge>
				</button><!-- End Messages Icon -->

				<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow messages hidden">
					<li class="dropdown-header">
						You have 3 new messages
						<a href={'#'}><span class="badge rounded-pill bg-primary ms-2 p-2">View all</span></a>
					</li>
					<li>
						<hr class="dropdown-divider" />
					</li>

					<li class="message-item">
						<a href={'#'}>
							<img src="assets/img/messages-1.jpg" alt="" class="rounded-circle" />
							<div>
								<h4>Maria Hudson</h4>
								<p>Velit asperiores et ducimus soluta repudiandae labore officia est ut...</p>
								<p>4 hrs. ago</p>
							</div>
						</a>
					</li>
					<li>
						<hr class="dropdown-divider" />
					</li>

					<li class="message-item">
						<a href={'#'}>
							<img src="assets/img/messages-2.jpg" alt="" class="rounded-circle" />
							<div>
								<h4>Anna Nelson</h4>
								<p>Velit asperiores et ducimus soluta repudiandae labore officia est ut...</p>
								<p>6 hrs. ago</p>
							</div>
						</a>
					</li>
					<li>
						<hr class="dropdown-divider" />
					</li>

					<li class="message-item">
						<a href={'#'}>
							<img src="assets/img/messages-3.jpg" alt="" class="rounded-circle" />
							<div>
								<h4>David Muldon</h4>
								<p>Velit asperiores et ducimus soluta repudiandae labore officia est ut...</p>
								<p>8 hrs. ago</p>
							</div>
						</a>
					</li>
					<li>
						<hr class="dropdown-divider" />
					</li>

					<li class="dropdown-footer">
						<a href={'#'}>Show all messages</a>
					</li>
				</ul>
				<!-- End Messages Dropdown Items -->
			</li>
			<!-- End Messages Nav -->

			<li class="relative pr-4">
				<button class="flex items-center text-[#012970]" data-bs-toggle="dropdown">
					<img src={ProfileImage} alt="Profile" class="max-h-[36px] rounded-[50%] align-middle" />
					<span
						class="hidden whitespace-nowrap pl-2 text-sm font-semibold after:ml-[.255em] after:inline-block after:border-x-[.3em] after:border-t-[.3em] after:border-solid after:border-[#012970] after:border-x-transparent after:align-[.255em] after:content-empty md:block"
						>K. Anderson</span
					>
				</button><!-- End Profile Iamge Icon -->

				<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow profile hidden">
					<li class="dropdown-header">
						<h6>Kevin Anderson</h6>
						<span>Web Designer</span>
					</li>
					<li>
						<hr class="dropdown-divider" />
					</li>

					<li>
						<a class="dropdown-item flex items-center" href="users-profile.html">
							<i class="bi bi-person"></i>
							<span>My Profile</span>
						</a>
					</li>
					<li>
						<hr class="dropdown-divider" />
					</li>

					<li>
						<a class="dropdown-item flex items-center" href="users-profile.html">
							<i class="bi bi-gear"></i>
							<span>Account Settings</span>
						</a>
					</li>
					<li>
						<hr class="dropdown-divider" />
					</li>

					<li>
						<a class="dropdown-item flex items-center" href="pages-faq.html">
							<i class="bi bi-question-circle"></i>
							<span>Need Help?</span>
						</a>
					</li>
					<li>
						<hr class="dropdown-divider" />
					</li>

					<li>
						<a class="dropdown-item flex items-center" href={'#'}>
							<i class="bi bi-box-arrow-right"></i>
							<span>Sign Out</span>
						</a>
					</li>
				</ul>
				<!-- End Profile Dropdown Items -->
			</li>
			<!-- End Profile Nav -->
		</ul>
	</nav>
	<!-- End Icons Navigation -->
</header>

<aside
	class="fixed bottom-0 left-0 top-[60px] z-[1029] w-[300px] overflow-y-auto bg-white p-5 shadow-[0px_0px_20px_rgba(1,_41,_112,_0.1)] transition-all duration-300 [scrollbar-color:_#aab7cf_transparent] [scrollbar-width:thin]"
>
	<ul class="sidebar-nav" id="sidebar-nav">
		{#each SidebarMenu as { link, subMenu, biIconClass, title }, index}
			{#if !biIconClass}
				<li class="mb-[5px] ml-[15px] mt-[10px] text-[11px] font-semibold uppercase text-[#899bbd]">
					{title}
				</li>
			{:else if !subMenu && link}
				<li class="mb-[5px]">
					<a
						class="flex items-center rounded-[4px] bg-[#f6f9ff] px-[15px] py-[10px] text-[15px] font-semibold text-[#012970] hover:bg-[#f6f9ff] hover:text-[#4154f1]"
						href={link}
						aria-label=" "
					>
						<i class="{biIconClass} mr-[10px] text-[16px]"></i>
						<span>{title}</span>
					</a>
				</li>
			{:else if subMenu}
				<li class="mb-[5px]">
					<button
						class="flex w-full items-center rounded-[4px] bg-[#f6f9ff] px-[15px] py-[10px] text-[15px] font-semibold text-[#012970] hover:bg-[#f6f9ff] hover:text-[#4154f1]"
						onclick={() =>
							SidebarMenu[index].refThis?.showing()
								? SidebarMenu[index].refThis?.hide()
								: SidebarMenu[index].refThis?.show()}
					>
						<i class="{biIconClass} mr-[10px] text-[16px]"></i>
						<span>{title}</span><i class="bi bi-chevron-down ml-auto"></i>
					</button>
					<DropdownMenu bind:this={SidebarMenu[index].refThis} collapseAtStart={true}>
						{#each subMenu as subMenuItem}
							<li>
								<a
									class="flex items-center py-[10px] pl-[40px] text-[14px] font-semibold text-[#012970]"
									href={subMenuItem.link}
									aria-label=" "
								>
									<i class="bi bi-circle mr-[8px] text-[6px] leading-[0]"></i><span
										>{subMenuItem.title}</span
									>
								</a>
							</li>
						{/each}
					</DropdownMenu>
				</li>
			{/if}
		{/each}
	</ul>
</aside>

<main id="main" class="mt-[60px] px-[30px] py-5 lg:ml-[300px]">
	{@render children()}
</main>

<footer class="border-t border-solid border-[#cddfff] py-5 text-sm lg:ml-[300px]">
	<div class="text-center text-[#012970]">
		&copy; Copyright <strong><span>Admin Template</span></strong>. All Rights Reserved
	</div>
	<div class="pt-[5px] text-center text-[13px] text-[#012970]">
		Designed by <a href="https://bootstrapmade.com/">BootstrapMade</a>
	</div>
</footer>

<button
	class="fixed bottom-[15px] right-[15px] z-[99999] hidden size-[40px] items-center justify-center rounded-[4px] bg-[#4154f1] transition-all duration-[.4s]"
	aria-label=" "
>
	<i class="bi bi-arrow-up-short text-2xl leading-[0] text-white"></i>
</button>
