<script>
	import '@fortawesome/fontawesome-free/css/fontawesome.min.css';
	import '@fortawesome/fontawesome-free/css/solid.min.css';
	import '@fortawesome/fontawesome-free/css/regular.min.css';
	import '@fortawesome/fontawesome-free/css/brands.min.css';
	import '../app.css';
	import LogoImage from '$assets/logo.png';
	import ProfileImage from '$assets/profile.jpg';
	import Badge from '$components/Badge.svelte';
	let { children } = $props();
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
		<i class="fa-solid fa-bars cursor-pointer pl-[10px] text-[32px] text-[#012970]"></i>
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
				<i class="fa-solid fa-magnifying-glass"></i>
			</button>
		</form>
	</div>
	<!-- End Search Bar -->

	<nav class="ml-auto">
		<ul class="flex items-center">
			<li class="nav-item block lg:hidden">
				<button class="nav-link nav-icon search-bar-toggle" aria-label=" ">
					<i class="bi bi-search"></i>
				</button>
			</li>
			<!-- End Search Icon-->

			<li class="relative">
				<button class="relative mr-[25px] text-2xl text-[#012970]">
					<i class="fa-regular fa-bell"></i>
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
					<i class="fa-regular fa-comment-dots"></i>
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
						class="after:content-empty hidden whitespace-nowrap pl-2 text-sm font-semibold after:ml-[.255em] after:inline-block after:border-x-[.3em] after:border-t-[.3em] after:border-solid after:border-[#012970] after:border-x-transparent after:align-[.255em] md:block"
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
		<li class="nav-item">
			<a class="nav-link" href="index.html">
				<i class="bi bi-grid"></i>
				<span>Dashboard</span>
			</a>
		</li>
		<!-- End Dashboard Nav -->

		<li class="nav-item">
			<a
				class="nav-link collapsed"
				data-bs-target="#components-nav"
				data-bs-toggle="collapse"
				href={'#'}
			>
				<i class="bi bi-menu-button-wide"></i><span>Components</span><i
					class="bi bi-chevron-down ms-auto"
				></i>
			</a>
			<ul id="components-nav" class="nav-content collapse" data-bs-parent="#sidebar-nav">
				<li>
					<a href="components-alerts.html">
						<i class="bi bi-circle"></i><span>Alerts</span>
					</a>
				</li>
				<li>
					<a href="components-accordion.html">
						<i class="bi bi-circle"></i><span>Accordion</span>
					</a>
				</li>
				<li>
					<a href="components-badges.html">
						<i class="bi bi-circle"></i><span>Badges</span>
					</a>
				</li>
				<li>
					<a href="components-breadcrumbs.html">
						<i class="bi bi-circle"></i><span>Breadcrumbs</span>
					</a>
				</li>
				<li>
					<a href="components-buttons.html">
						<i class="bi bi-circle"></i><span>Buttons</span>
					</a>
				</li>
				<li>
					<a href="components-cards.html">
						<i class="bi bi-circle"></i><span>Cards</span>
					</a>
				</li>
				<li>
					<a href="components-carousel.html">
						<i class="bi bi-circle"></i><span>Carousel</span>
					</a>
				</li>
				<li>
					<a href="components-list-group.html">
						<i class="bi bi-circle"></i><span>List group</span>
					</a>
				</li>
				<li>
					<a href="components-modal.html">
						<i class="bi bi-circle"></i><span>Modal</span>
					</a>
				</li>
				<li>
					<a href="components-tabs.html">
						<i class="bi bi-circle"></i><span>Tabs</span>
					</a>
				</li>
				<li>
					<a href="components-pagination.html">
						<i class="bi bi-circle"></i><span>Pagination</span>
					</a>
				</li>
				<li>
					<a href="components-progress.html">
						<i class="bi bi-circle"></i><span>Progress</span>
					</a>
				</li>
				<li>
					<a href="components-spinners.html">
						<i class="bi bi-circle"></i><span>Spinners</span>
					</a>
				</li>
				<li>
					<a href="components-tooltips.html">
						<i class="bi bi-circle"></i><span>Tooltips</span>
					</a>
				</li>
			</ul>
		</li>
		<!-- End Components Nav -->

		<li class="nav-item">
			<a
				class="nav-link collapsed"
				data-bs-target="#forms-nav"
				data-bs-toggle="collapse"
				href={'#'}
			>
				<i class="bi bi-journal-text"></i><span>Forms</span><i class="bi bi-chevron-down ms-auto"
				></i>
			</a>
			<ul id="forms-nav" class="nav-content collapse" data-bs-parent="#sidebar-nav">
				<li>
					<a href="forms-elements.html">
						<i class="bi bi-circle"></i><span>Form Elements</span>
					</a>
				</li>
				<li>
					<a href="forms-layouts.html">
						<i class="bi bi-circle"></i><span>Form Layouts</span>
					</a>
				</li>
				<li>
					<a href="forms-editors.html">
						<i class="bi bi-circle"></i><span>Form Editors</span>
					</a>
				</li>
				<li>
					<a href="forms-validation.html">
						<i class="bi bi-circle"></i><span>Form Validation</span>
					</a>
				</li>
			</ul>
		</li>
		<!-- End Forms Nav -->

		<li class="nav-item">
			<a
				class="nav-link collapsed"
				data-bs-target="#tables-nav"
				data-bs-toggle="collapse"
				href={'#'}
			>
				<i class="bi bi-layout-text-window-reverse"></i><span>Tables</span><i
					class="bi bi-chevron-down ms-auto"
				></i>
			</a>
			<ul id="tables-nav" class="nav-content collapse" data-bs-parent="#sidebar-nav">
				<li>
					<a href="tables-general.html">
						<i class="bi bi-circle"></i><span>General Tables</span>
					</a>
				</li>
				<li>
					<a href="tables-data.html">
						<i class="bi bi-circle"></i><span>Data Tables</span>
					</a>
				</li>
			</ul>
		</li>
		<!-- End Tables Nav -->

		<li class="nav-item">
			<a
				class="nav-link collapsed"
				data-bs-target="#charts-nav"
				data-bs-toggle="collapse"
				href={'#'}
			>
				<i class="bi bi-bar-chart"></i><span>Charts</span><i class="bi bi-chevron-down ms-auto"></i>
			</a>
			<ul id="charts-nav" class="nav-content collapse" data-bs-parent="#sidebar-nav">
				<li>
					<a href="charts-chartjs.html">
						<i class="bi bi-circle"></i><span>Chart.js</span>
					</a>
				</li>
				<li>
					<a href="charts-apexcharts.html">
						<i class="bi bi-circle"></i><span>ApexCharts</span>
					</a>
				</li>
				<li>
					<a href="charts-echarts.html">
						<i class="bi bi-circle"></i><span>ECharts</span>
					</a>
				</li>
			</ul>
		</li>
		<!-- End Charts Nav -->

		<li class="nav-item">
			<a
				class="nav-link collapsed"
				data-bs-target="#icons-nav"
				data-bs-toggle="collapse"
				href={'#'}
			>
				<i class="bi bi-gem"></i><span>Icons</span><i class="bi bi-chevron-down ms-auto"></i>
			</a>
			<ul id="icons-nav" class="nav-content collapse" data-bs-parent="#sidebar-nav">
				<li>
					<a href="icons-bootstrap.html">
						<i class="bi bi-circle"></i><span>Bootstrap Icons</span>
					</a>
				</li>
				<li>
					<a href="icons-remix.html">
						<i class="bi bi-circle"></i><span>Remix Icons</span>
					</a>
				</li>
				<li>
					<a href="icons-boxicons.html">
						<i class="bi bi-circle"></i><span>Boxicons</span>
					</a>
				</li>
			</ul>
		</li>
		<!-- End Icons Nav -->

		<li class="nav-heading">Pages</li>

		<li class="nav-item">
			<a class="nav-link collapsed" href="users-profile.html">
				<i class="bi bi-person"></i>
				<span>Profile</span>
			</a>
		</li>
		<!-- End Profile Page Nav -->

		<li class="nav-item">
			<a class="nav-link collapsed" href="pages-faq.html">
				<i class="bi bi-question-circle"></i>
				<span>F.A.Q</span>
			</a>
		</li>
		<!-- End F.A.Q Page Nav -->

		<li class="nav-item">
			<a class="nav-link collapsed" href="pages-contact.html">
				<i class="bi bi-envelope"></i>
				<span>Contact</span>
			</a>
		</li>
		<!-- End Contact Page Nav -->

		<li class="nav-item">
			<a class="nav-link collapsed" href="pages-register.html">
				<i class="bi bi-card-list"></i>
				<span>Register</span>
			</a>
		</li>
		<!-- End Register Page Nav -->

		<li class="nav-item">
			<a class="nav-link collapsed" href="pages-login.html">
				<i class="bi bi-box-arrow-in-right"></i>
				<span>Login</span>
			</a>
		</li>
		<!-- End Login Page Nav -->

		<li class="nav-item">
			<a class="nav-link collapsed" href="pages-error-404.html">
				<i class="bi bi-dash-circle"></i>
				<span>Error 404</span>
			</a>
		</li>
		<!-- End Error 404 Page Nav -->

		<li class="nav-item">
			<a class="nav-link collapsed" href="pages-blank.html">
				<i class="bi bi-file-earmark"></i>
				<span>Blank</span>
			</a>
		</li>
		<!-- End Blank Page Nav -->
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
	class="fixed bottom-[15px] right-[15px] z-[99999] flex size-[40px] items-center justify-center rounded-[4px] bg-[#4154f1] transition-all duration-[.4s]"
	aria-label=" "
>
	<i class="fa-solid fa-arrow-up text-sm leading-[0] text-white"></i>
</button>
