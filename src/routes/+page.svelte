<svelte:head>
	<title>Dashboard - NiceAdmin Bootstrap Template</title>
	<meta content="" name="description" />
	<meta content="" name="keywords" />
</svelte:head>

<main id="main" class="main">
	<div class="pagetitle">
		<h1>Dashboard</h1>
		<nav>
			<ol class="breadcrumb">
				<li class="breadcrumb-item"><a href="index.html">Home</a></li>
				<li class="breadcrumb-item active">Dashboard</li>
			</ol>
		</nav>
	</div>
	<!-- End Page Title -->

	<section class="section dashboard">
		<div class="row">
			<!-- Left side columns -->
			<div class="col-lg-8">
				<div class="row">
					<!-- Sales Card -->
					<div class="col-xxl-4 col-md-6">
						<div class="card info-card sales-card">
							<div class="filter">
								<a class="icon" href="#" data-bs-toggle="dropdown"
									><i class="bi bi-three-dots"></i></a
								>
								<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow">
									<li class="dropdown-header text-start">
										<h6>Filter</h6>
									</li>

									<li><a class="dropdown-item" href="#">Today</a></li>
									<li><a class="dropdown-item" href="#">This Month</a></li>
									<li><a class="dropdown-item" href="#">This Year</a></li>
								</ul>
							</div>

							<div class="card-body">
								<h5 class="card-title">Sales <span>| Today</span></h5>

								<div class="d-flex align-items-center">
									<div
										class="card-icon rounded-circle d-flex align-items-center justify-content-center"
									>
										<i class="bi bi-cart"></i>
									</div>
									<div class="ps-3">
										<h6>145</h6>
										<span class="text-success small fw-bold pt-1">12%</span>
										<span class="text-muted small ps-1 pt-2">increase</span>
									</div>
								</div>
							</div>
						</div>
					</div>
					<!-- End Sales Card -->

					<!-- Revenue Card -->
					<div class="col-xxl-4 col-md-6">
						<div class="card info-card revenue-card">
							<div class="filter">
								<a class="icon" href="#" data-bs-toggle="dropdown"
									><i class="bi bi-three-dots"></i></a
								>
								<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow">
									<li class="dropdown-header text-start">
										<h6>Filter</h6>
									</li>

									<li><a class="dropdown-item" href="#">Today</a></li>
									<li><a class="dropdown-item" href="#">This Month</a></li>
									<li><a class="dropdown-item" href="#">This Year</a></li>
								</ul>
							</div>

							<div class="card-body">
								<h5 class="card-title">Revenue <span>| This Month</span></h5>

								<div class="d-flex align-items-center">
									<div
										class="card-icon rounded-circle d-flex align-items-center justify-content-center"
									>
										<i class="bi bi-currency-dollar"></i>
									</div>
									<div class="ps-3">
										<h6>$3,264</h6>
										<span class="text-success small fw-bold pt-1">8%</span>
										<span class="text-muted small ps-1 pt-2">increase</span>
									</div>
								</div>
							</div>
						</div>
					</div>
					<!-- End Revenue Card -->

					<!-- Customers Card -->
					<div class="col-xxl-4 col-xl-12">
						<div class="card info-card customers-card">
							<div class="filter">
								<a class="icon" href="#" data-bs-toggle="dropdown"
									><i class="bi bi-three-dots"></i></a
								>
								<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow">
									<li class="dropdown-header text-start">
										<h6>Filter</h6>
									</li>

									<li><a class="dropdown-item" href="#">Today</a></li>
									<li><a class="dropdown-item" href="#">This Month</a></li>
									<li><a class="dropdown-item" href="#">This Year</a></li>
								</ul>
							</div>

							<div class="card-body">
								<h5 class="card-title">Customers <span>| This Year</span></h5>

								<div class="d-flex align-items-center">
									<div
										class="card-icon rounded-circle d-flex align-items-center justify-content-center"
									>
										<i class="bi bi-people"></i>
									</div>
									<div class="ps-3">
										<h6>1244</h6>
										<span class="text-danger small fw-bold pt-1">12%</span>
										<span class="text-muted small ps-1 pt-2">decrease</span>
									</div>
								</div>
							</div>
						</div>
					</div>
					<!-- End Customers Card -->

					<!-- Reports -->
					<div class="col-12">
						<div class="card">
							<div class="filter">
								<a class="icon" href="#" data-bs-toggle="dropdown"
									><i class="bi bi-three-dots"></i></a
								>
								<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow">
									<li class="dropdown-header text-start">
										<h6>Filter</h6>
									</li>

									<li><a class="dropdown-item" href="#">Today</a></li>
									<li><a class="dropdown-item" href="#">This Month</a></li>
									<li><a class="dropdown-item" href="#">This Year</a></li>
								</ul>
							</div>

							<div class="card-body">
								<h5 class="card-title">Reports <span>/Today</span></h5>

								<!-- Line Chart -->
								<div id="reportsChart" class="" style="min-height: 365px;">
									<div
										id="apexchartslqxyiohfg"
										class="apexcharts-canvas apexchartslqxyiohfg apexcharts-theme-"
										style="width: 725px; height: 350px;"
									>
										<svg
											id="SvgjsSvg2277"
											width="725"
											height="350"
											xmlns="http://www.w3.org/2000/svg"
											version="1.1"
											xmlns:xlink="http://www.w3.org/1999/xlink"
											xmlns:svgjs="http://svgjs.dev"
											class="apexcharts-svg apexcharts-zoomable"
											xmlns:data="ApexChartsNS"
											transform="translate(0, 0)"
											><foreignObject x="0" y="0" width="725" height="350"
												><div
													class="apexcharts-legend apexcharts-align-center apx-legend-position-bottom"
													xmlns="http://www.w3.org/1999/xhtml"
													style="inset: auto 0px 1px; position: absolute; max-height: 175px;"
												>
													<div
														class="apexcharts-legend-series"
														rel="1"
														seriesname="Sales"
														data:collapsed="false"
														style="margin: 4px 5px;"
													>
														<span
															class="apexcharts-legend-marker"
															rel="1"
															data:collapsed="false"
															style="height: 16px; width: 16px; left: 0px; top: 0px;"
															><svg
																id="SvgjsSvg2280"
																width="100%"
																height="100%"
																xmlns="http://www.w3.org/2000/svg"
																version="1.1"
																xmlns:xlink="http://www.w3.org/1999/xlink"
																xmlns:svgjs="http://svgjs.dev"
																><defs id="SvgjsDefs2281"
																	><clipPath id="gridRectMasklqxyiohfg"
																		><rect
																			id="SvgjsRect2299"
																			width="681.4823236465454"
																			height="270.6799995422363"
																			x="-3"
																			y="-3"
																			rx="0"
																			ry="0"
																			opacity="1"
																			stroke-width="0"
																			stroke="none"
																			stroke-dasharray="0"
																			fill="#fff"
																		></rect></clipPath
																	><clipPath id="forecastMasklqxyiohfg"></clipPath><clipPath
																		id="nonForecastMasklqxyiohfg"
																	></clipPath><clipPath id="gridRectMarkerMasklqxyiohfg"
																		><rect
																			id="SvgjsRect2300"
																			width="723.4823236465454"
																			height="312.6799995422363"
																			x="-24"
																			y="-24"
																			rx="0"
																			ry="0"
																			opacity="1"
																			stroke-width="0"
																			stroke="none"
																			stroke-dasharray="0"
																			fill="#fff"
																		></rect></clipPath
																	></defs
																><path
																	id="SvgjsPath2282"
																	d="M 0, 0 
           m -7, 0 
           a 7,7 0 1,0 14,0 
           a 7,7 0 1,0 -14,0"
																	fill="#4154f1"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="1"
																	stroke-dasharray="0"
																	cx="0"
																	cy="0"
																	shape="circle"
																	class="apexcharts-legend-marker apexcharts-marker apexcharts-marker-circle"
																	style="transform: translate(50%, 50%);"
																></path></svg
															></span
														><span
															class="apexcharts-legend-text"
															rel="1"
															i="0"
															data:default-text="Sales"
															data:collapsed="false"
															style="color: rgb(55, 61, 63); font-size: 12px; font-weight: 400; font-family: Helvetica, Arial, sans-serif;"
															>Sales</span
														>
													</div>
													<div
														class="apexcharts-legend-series"
														rel="2"
														seriesname="Revenue"
														data:collapsed="false"
														style="margin: 4px 5px;"
													>
														<span
															class="apexcharts-legend-marker"
															rel="2"
															data:collapsed="false"
															style="height: 16px; width: 16px; left: 0px; top: 0px;"
															><svg
																id="SvgjsSvg2283"
																width="100%"
																height="100%"
																xmlns="http://www.w3.org/2000/svg"
																version="1.1"
																xmlns:xlink="http://www.w3.org/1999/xlink"
																xmlns:svgjs="http://svgjs.dev"
																><defs id="SvgjsDefs2284"></defs><path
																	id="SvgjsPath2285"
																	d="M 0, 0 
           m -7, 0 
           a 7,7 0 1,0 14,0 
           a 7,7 0 1,0 -14,0"
																	fill="#2eca6a"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="1"
																	stroke-dasharray="0"
																	cx="0"
																	cy="0"
																	shape="circle"
																	class="apexcharts-legend-marker apexcharts-marker apexcharts-marker-circle"
																	style="transform: translate(50%, 50%);"
																></path></svg
															></span
														><span
															class="apexcharts-legend-text"
															rel="2"
															i="1"
															data:default-text="Revenue"
															data:collapsed="false"
															style="color: rgb(55, 61, 63); font-size: 12px; font-weight: 400; font-family: Helvetica, Arial, sans-serif;"
															>Revenue</span
														>
													</div>
													<div
														class="apexcharts-legend-series"
														rel="3"
														seriesname="Customers"
														data:collapsed="false"
														style="margin: 4px 5px;"
													>
														<span
															class="apexcharts-legend-marker"
															rel="3"
															data:collapsed="false"
															style="height: 16px; width: 16px; left: 0px; top: 0px;"
															><svg
																id="SvgjsSvg2286"
																width="100%"
																height="100%"
																xmlns="http://www.w3.org/2000/svg"
																version="1.1"
																xmlns:xlink="http://www.w3.org/1999/xlink"
																xmlns:svgjs="http://svgjs.dev"
																><defs id="SvgjsDefs2287"></defs><path
																	id="SvgjsPath2288"
																	d="M 0, 0 
           m -7, 0 
           a 7,7 0 1,0 14,0 
           a 7,7 0 1,0 -14,0"
																	fill="#ff771d"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="1"
																	stroke-dasharray="0"
																	cx="0"
																	cy="0"
																	shape="circle"
																	class="apexcharts-legend-marker apexcharts-marker apexcharts-marker-circle"
																	style="transform: translate(50%, 50%);"
																></path></svg
															></span
														><span
															class="apexcharts-legend-text"
															rel="3"
															i="2"
															data:default-text="Customers"
															data:collapsed="false"
															style="color: rgb(55, 61, 63); font-size: 12px; font-weight: 400; font-family: Helvetica, Arial, sans-serif;"
															>Customers</span
														>
													</div>
												</div>
												<style type="text/css">
													.apexcharts-legend {
														display: flex;
														overflow: auto;
														padding: 0 10px;
													}
													.apexcharts-legend.apx-legend-position-bottom,
													.apexcharts-legend.apx-legend-position-top {
														flex-wrap: wrap;
													}
													.apexcharts-legend.apx-legend-position-right,
													.apexcharts-legend.apx-legend-position-left {
														flex-direction: column;
														bottom: 0;
													}
													.apexcharts-legend.apx-legend-position-bottom.apexcharts-align-left,
													.apexcharts-legend.apx-legend-position-top.apexcharts-align-left,
													.apexcharts-legend.apx-legend-position-right,
													.apexcharts-legend.apx-legend-position-left {
														justify-content: flex-start;
													}
													.apexcharts-legend.apx-legend-position-bottom.apexcharts-align-center,
													.apexcharts-legend.apx-legend-position-top.apexcharts-align-center {
														justify-content: center;
													}
													.apexcharts-legend.apx-legend-position-bottom.apexcharts-align-right,
													.apexcharts-legend.apx-legend-position-top.apexcharts-align-right {
														justify-content: flex-end;
													}
													.apexcharts-legend-series {
														cursor: pointer;
														line-height: normal;
														display: flex;
														align-items: center;
													}
													.apexcharts-legend-text {
														position: relative;
														font-size: 14px;
													}
													.apexcharts-legend-text *,
													.apexcharts-legend-marker * {
														pointer-events: none;
													}
													.apexcharts-legend-marker {
														position: relative;
														display: flex;
														align-items: center;
														justify-content: center;
														cursor: pointer;
														margin-right: 1px;
													}

													.apexcharts-legend-series.apexcharts-no-click {
														cursor: auto;
													}
													.apexcharts-legend .apexcharts-hidden-zero-series,
													.apexcharts-legend .apexcharts-hidden-null-series {
														display: none !important;
													}
													.apexcharts-inactive-legend {
														opacity: 0.45;
													}
												</style></foreignObject
											><rect
												id="SvgjsRect2294"
												width="0"
												height="0"
												x="0"
												y="0"
												rx="0"
												ry="0"
												opacity="1"
												stroke-width="0"
												stroke="none"
												stroke-dasharray="0"
												fill="#fefefe"
											></rect><g
												id="SvgjsG2301"
												class="apexcharts-datalabels-group"
												transform="translate(0, 0) scale(1)"
											></g><g
												id="SvgjsG2302"
												class="apexcharts-datalabels-group"
												transform="translate(0, 0) scale(1)"
											></g><g
												id="SvgjsG2419"
												class="apexcharts-yaxis"
												rel="0"
												transform="translate(9.51767635345459, 0)"
												><g id="SvgjsG2420" class="apexcharts-yaxis-texts-g"
													><text
														id="SvgjsText2422"
														font-family="Helvetica, Arial, sans-serif"
														x="20"
														y="33.666666666666664"
														text-anchor="end"
														dominant-baseline="auto"
														font-size="11px"
														font-weight="400"
														fill="#373d3f"
														class="apexcharts-text apexcharts-yaxis-label"
														style="font-family: Helvetica, Arial, sans-serif;"
														><tspan id="SvgjsTspan2423">90</tspan><title>90</title></text
													><text
														id="SvgjsText2425"
														font-family="Helvetica, Arial, sans-serif"
														x="20"
														y="63.07555550469292"
														text-anchor="end"
														dominant-baseline="auto"
														font-size="11px"
														font-weight="400"
														fill="#373d3f"
														class="apexcharts-text apexcharts-yaxis-label"
														style="font-family: Helvetica, Arial, sans-serif;"
														><tspan id="SvgjsTspan2426">80</tspan><title>80</title></text
													><text
														id="SvgjsText2428"
														font-family="Helvetica, Arial, sans-serif"
														x="20"
														y="92.48444434271917"
														text-anchor="end"
														dominant-baseline="auto"
														font-size="11px"
														font-weight="400"
														fill="#373d3f"
														class="apexcharts-text apexcharts-yaxis-label"
														style="font-family: Helvetica, Arial, sans-serif;"
														><tspan id="SvgjsTspan2429">70</tspan><title>70</title></text
													><text
														id="SvgjsText2431"
														font-family="Helvetica, Arial, sans-serif"
														x="20"
														y="121.89333318074543"
														text-anchor="end"
														dominant-baseline="auto"
														font-size="11px"
														font-weight="400"
														fill="#373d3f"
														class="apexcharts-text apexcharts-yaxis-label"
														style="font-family: Helvetica, Arial, sans-serif;"
														><tspan id="SvgjsTspan2432">60</tspan><title>60</title></text
													><text
														id="SvgjsText2434"
														font-family="Helvetica, Arial, sans-serif"
														x="20"
														y="151.3022220187717"
														text-anchor="end"
														dominant-baseline="auto"
														font-size="11px"
														font-weight="400"
														fill="#373d3f"
														class="apexcharts-text apexcharts-yaxis-label"
														style="font-family: Helvetica, Arial, sans-serif;"
														><tspan id="SvgjsTspan2435">50</tspan><title>50</title></text
													><text
														id="SvgjsText2437"
														font-family="Helvetica, Arial, sans-serif"
														x="20"
														y="180.71111085679794"
														text-anchor="end"
														dominant-baseline="auto"
														font-size="11px"
														font-weight="400"
														fill="#373d3f"
														class="apexcharts-text apexcharts-yaxis-label"
														style="font-family: Helvetica, Arial, sans-serif;"
														><tspan id="SvgjsTspan2438">40</tspan><title>40</title></text
													><text
														id="SvgjsText2440"
														font-family="Helvetica, Arial, sans-serif"
														x="20"
														y="210.1199996948242"
														text-anchor="end"
														dominant-baseline="auto"
														font-size="11px"
														font-weight="400"
														fill="#373d3f"
														class="apexcharts-text apexcharts-yaxis-label"
														style="font-family: Helvetica, Arial, sans-serif;"
														><tspan id="SvgjsTspan2441">30</tspan><title>30</title></text
													><text
														id="SvgjsText2443"
														font-family="Helvetica, Arial, sans-serif"
														x="20"
														y="239.52888853285046"
														text-anchor="end"
														dominant-baseline="auto"
														font-size="11px"
														font-weight="400"
														fill="#373d3f"
														class="apexcharts-text apexcharts-yaxis-label"
														style="font-family: Helvetica, Arial, sans-serif;"
														><tspan id="SvgjsTspan2444">20</tspan><title>20</title></text
													><text
														id="SvgjsText2446"
														font-family="Helvetica, Arial, sans-serif"
														x="20"
														y="268.9377773708767"
														text-anchor="end"
														dominant-baseline="auto"
														font-size="11px"
														font-weight="400"
														fill="#373d3f"
														class="apexcharts-text apexcharts-yaxis-label"
														style="font-family: Helvetica, Arial, sans-serif;"
														><tspan id="SvgjsTspan2447">10</tspan><title>10</title></text
													><text
														id="SvgjsText2449"
														font-family="Helvetica, Arial, sans-serif"
														x="20"
														y="298.34666620890295"
														text-anchor="end"
														dominant-baseline="auto"
														font-size="11px"
														font-weight="400"
														fill="#373d3f"
														class="apexcharts-text apexcharts-yaxis-label"
														style="font-family: Helvetica, Arial, sans-serif;"
														><tspan id="SvgjsTspan2450">0</tspan><title>0</title></text
													></g
												></g
											><g
												id="SvgjsG2279"
												class="apexcharts-inner apexcharts-graphical"
												transform="translate(39.51767635345459, 30)"
												><defs id="SvgjsDefs2278"
													><linearGradient id="SvgjsLinearGradient2320" x1="0" y1="0" x2="0" y2="1"
														><stop
															id="SvgjsStop2321"
															stop-opacity="0.3"
															stop-color="rgba(65,84,241,0.3)"
															offset="0"
														></stop><stop
															id="SvgjsStop2322"
															stop-opacity="0.4"
															stop-color="rgba(255,255,255,0.4)"
															offset="0.9"
														></stop><stop
															id="SvgjsStop2323"
															stop-opacity="0.4"
															stop-color="rgba(255,255,255,0.4)"
															offset="1"
														></stop></linearGradient
													><linearGradient id="SvgjsLinearGradient2342" x1="0" y1="0" x2="0" y2="1"
														><stop
															id="SvgjsStop2343"
															stop-opacity="0.3"
															stop-color="rgba(46,202,106,0.3)"
															offset="0"
														></stop><stop
															id="SvgjsStop2344"
															stop-opacity="0.4"
															stop-color="rgba(255,255,255,0.4)"
															offset="0.9"
														></stop><stop
															id="SvgjsStop2345"
															stop-opacity="0.4"
															stop-color="rgba(255,255,255,0.4)"
															offset="1"
														></stop></linearGradient
													><linearGradient id="SvgjsLinearGradient2364" x1="0" y1="0" x2="0" y2="1"
														><stop
															id="SvgjsStop2365"
															stop-opacity="0.3"
															stop-color="rgba(255,119,29,0.3)"
															offset="0"
														></stop><stop
															id="SvgjsStop2366"
															stop-opacity="0.4"
															stop-color="rgba(255,255,255,0.4)"
															offset="0.9"
														></stop><stop
															id="SvgjsStop2367"
															stop-opacity="0.4"
															stop-color="rgba(255,255,255,0.4)"
															offset="1"
														></stop></linearGradient
													></defs
												><line
													id="SvgjsLine2295"
													x1="0"
													y1="0"
													x2="0"
													y2="211.009375"
													stroke="#b6b6b6"
													stroke-dasharray="3"
													stroke-linecap="butt"
													class="apexcharts-xcrosshairs"
													x="0"
													y="0"
													width="1"
													height="211.009375"
													fill="#b1b9c4"
													filter="none"
													fill-opacity="0.9"
													stroke-width="1"
												></line><line
													id="SvgjsLine2374"
													x1="0"
													y1="264.6799995422363"
													x2="0"
													y2="270.6799995422363"
													stroke="#e0e0e0"
													stroke-dasharray="0"
													stroke-linecap="butt"
													class="apexcharts-xaxis-tick"
												></line><line
													id="SvgjsLine2375"
													x1="103.92035748408392"
													y1="264.6799995422363"
													x2="103.92035748408392"
													y2="270.6799995422363"
													stroke="#e0e0e0"
													stroke-dasharray="0"
													stroke-linecap="butt"
													class="apexcharts-xaxis-tick"
												></line><line
													id="SvgjsLine2376"
													x1="207.84071496816784"
													y1="264.6799995422363"
													x2="207.84071496816784"
													y2="270.6799995422363"
													stroke="#e0e0e0"
													stroke-dasharray="0"
													stroke-linecap="butt"
													class="apexcharts-xaxis-tick"
												></line><line
													id="SvgjsLine2377"
													x1="311.76107245225177"
													y1="264.6799995422363"
													x2="311.76107245225177"
													y2="270.6799995422363"
													stroke="#e0e0e0"
													stroke-dasharray="0"
													stroke-linecap="butt"
													class="apexcharts-xaxis-tick"
												></line><line
													id="SvgjsLine2378"
													x1="415.6814299363357"
													y1="264.6799995422363"
													x2="415.6814299363357"
													y2="270.6799995422363"
													stroke="#e0e0e0"
													stroke-dasharray="0"
													stroke-linecap="butt"
													class="apexcharts-xaxis-tick"
												></line><line
													id="SvgjsLine2379"
													x1="519.6017874204197"
													y1="264.6799995422363"
													x2="519.6017874204197"
													y2="270.6799995422363"
													stroke="#e0e0e0"
													stroke-dasharray="0"
													stroke-linecap="butt"
													class="apexcharts-xaxis-tick"
												></line><line
													id="SvgjsLine2380"
													x1="623.5221449045036"
													y1="264.6799995422363"
													x2="623.5221449045036"
													y2="270.6799995422363"
													stroke="#e0e0e0"
													stroke-dasharray="0"
													stroke-linecap="butt"
													class="apexcharts-xaxis-tick"
												></line><g id="SvgjsG2370" class="apexcharts-grid"
													><g id="SvgjsG2371" class="apexcharts-gridlines-horizontal"
														><line
															id="SvgjsLine2382"
															x1="0"
															y1="29.408888838026257"
															x2="675.4823236465454"
															y2="29.408888838026257"
															stroke="#e0e0e0"
															stroke-dasharray="0"
															stroke-linecap="butt"
															class="apexcharts-gridline"
														></line><line
															id="SvgjsLine2383"
															x1="0"
															y1="58.817777676052515"
															x2="675.4823236465454"
															y2="58.817777676052515"
															stroke="#e0e0e0"
															stroke-dasharray="0"
															stroke-linecap="butt"
															class="apexcharts-gridline"
														></line><line
															id="SvgjsLine2384"
															x1="0"
															y1="88.22666651407877"
															x2="675.4823236465454"
															y2="88.22666651407877"
															stroke="#e0e0e0"
															stroke-dasharray="0"
															stroke-linecap="butt"
															class="apexcharts-gridline"
														></line><line
															id="SvgjsLine2385"
															x1="0"
															y1="117.63555535210503"
															x2="675.4823236465454"
															y2="117.63555535210503"
															stroke="#e0e0e0"
															stroke-dasharray="0"
															stroke-linecap="butt"
															class="apexcharts-gridline"
														></line><line
															id="SvgjsLine2386"
															x1="0"
															y1="147.0444441901313"
															x2="675.4823236465454"
															y2="147.0444441901313"
															stroke="#e0e0e0"
															stroke-dasharray="0"
															stroke-linecap="butt"
															class="apexcharts-gridline"
														></line><line
															id="SvgjsLine2387"
															x1="0"
															y1="176.45333302815754"
															x2="675.4823236465454"
															y2="176.45333302815754"
															stroke="#e0e0e0"
															stroke-dasharray="0"
															stroke-linecap="butt"
															class="apexcharts-gridline"
														></line><line
															id="SvgjsLine2388"
															x1="0"
															y1="205.8622218661838"
															x2="675.4823236465454"
															y2="205.8622218661838"
															stroke="#e0e0e0"
															stroke-dasharray="0"
															stroke-linecap="butt"
															class="apexcharts-gridline"
														></line><line
															id="SvgjsLine2389"
															x1="0"
															y1="235.27111070421006"
															x2="675.4823236465454"
															y2="235.27111070421006"
															stroke="#e0e0e0"
															stroke-dasharray="0"
															stroke-linecap="butt"
															class="apexcharts-gridline"
														></line></g
													><g id="SvgjsG2372" class="apexcharts-gridlines-vertical"></g><line
														id="SvgjsLine2392"
														x1="0"
														y1="264.6799995422363"
														x2="675.4823236465454"
														y2="264.6799995422363"
														stroke="transparent"
														stroke-dasharray="0"
														stroke-linecap="butt"
													></line><line
														id="SvgjsLine2391"
														x1="0"
														y1="1"
														x2="0"
														y2="264.6799995422363"
														stroke="transparent"
														stroke-dasharray="0"
														stroke-linecap="butt"
													></line></g
												><g id="SvgjsG2373" class="apexcharts-grid-borders"
													><line
														id="SvgjsLine2381"
														x1="0"
														y1="0"
														x2="675.4823236465454"
														y2="0"
														stroke="#e0e0e0"
														stroke-dasharray="0"
														stroke-linecap="butt"
														class="apexcharts-gridline"
													></line><line
														id="SvgjsLine2390"
														x1="0"
														y1="264.6799995422363"
														x2="675.4823236465454"
														y2="264.6799995422363"
														stroke="#e0e0e0"
														stroke-dasharray="0"
														stroke-linecap="butt"
														class="apexcharts-gridline"
													></line><line
														id="SvgjsLine2418"
														x1="0"
														y1="264.6799995422363"
														x2="675.4823236465454"
														y2="264.6799995422363"
														stroke="#e0e0e0"
														stroke-dasharray="0"
														stroke-width="1"
														stroke-linecap="butt"
													></line></g
												><g id="SvgjsG2303" class="apexcharts-area-series apexcharts-plot-series"
													><g
														id="SvgjsG2304"
														class="apexcharts-series"
														zIndex="0"
														seriesName="Sales"
														data:longestSeries="true"
														rel="1"
														data:realIndex="0"
														><path
															id="SvgjsPath2324"
															d="M 0 173.5124441443549C 54.55818767914405 173.5124441443549 101.3223485469818 147.0444441901313 155.88053622612586 147.0444441901313C 192.25266134555523 147.0444441901313 223.4287685907804 182.3351107957628 259.8008937102098 182.3351107957628C 296.17301882963915 182.3351107957628 327.3491260748643 114.69466646830242 363.72125119429364 114.69466646830242C 400.093376313723 114.69466646830242 431.2694835589482 141.16266642252606 467.64160867837757 141.16266642252606C 504.01373379780694 141.16266642252606 535.1898410430321 23.52711107042103 571.5619661624614 23.52711107042103C 607.9340912818908 23.52711107042103 639.110198527116 99.99022204928929 675.4823236465454 99.99022204928929C 675.4823236465454 99.99022204928929 675.4823236465454 99.99022204928929 675.4823236465454 264.6799995422363 L 0 264.6799995422363z"
															fill="url(#SvgjsLinearGradient2320)"
															fill-opacity="1"
															stroke-opacity="1"
															stroke-linecap="butt"
															stroke-width="0"
															stroke-dasharray="0"
															class="apexcharts-area"
															index="0"
															clip-path="url(#gridRectMasklqxyiohfg)"
															pathTo="M 0 173.5124441443549C 54.55818767914405 173.5124441443549 101.3223485469818 147.0444441901313 155.88053622612586 147.0444441901313C 192.25266134555523 147.0444441901313 223.4287685907804 182.3351107957628 259.8008937102098 182.3351107957628C 296.17301882963915 182.3351107957628 327.3491260748643 114.69466646830242 363.72125119429364 114.69466646830242C 400.093376313723 114.69466646830242 431.2694835589482 141.16266642252606 467.64160867837757 141.16266642252606C 504.01373379780694 141.16266642252606 535.1898410430321 23.52711107042103 571.5619661624614 23.52711107042103C 607.9340912818908 23.52711107042103 639.110198527116 99.99022204928929 675.4823236465454 99.99022204928929C 675.4823236465454 99.99022204928929 675.4823236465454 99.99022204928929 675.4823236465454 264.6799995422363 L 0 264.6799995422363z"
															pathFrom="M 0 264.6799995422363 L 0 264.6799995422363 L 155.88053622612586 264.6799995422363 L 259.8008937102098 264.6799995422363 L 363.72125119429364 264.6799995422363 L 467.64160867837757 264.6799995422363 L 571.5619661624614 264.6799995422363 L 675.4823236465454 264.6799995422363z"
														></path><path
															id="SvgjsPath2325"
															d="M 0 173.5124441443549C 54.55818767914405 173.5124441443549 101.3223485469818 147.0444441901313 155.88053622612586 147.0444441901313C 192.25266134555523 147.0444441901313 223.4287685907804 182.3351107957628 259.8008937102098 182.3351107957628C 296.17301882963915 182.3351107957628 327.3491260748643 114.69466646830242 363.72125119429364 114.69466646830242C 400.093376313723 114.69466646830242 431.2694835589482 141.16266642252606 467.64160867837757 141.16266642252606C 504.01373379780694 141.16266642252606 535.1898410430321 23.52711107042103 571.5619661624614 23.52711107042103C 607.9340912818908 23.52711107042103 639.110198527116 99.99022204928929 675.4823236465454 99.99022204928929"
															fill="none"
															fill-opacity="1"
															stroke="#4154f1"
															stroke-opacity="1"
															stroke-linecap="butt"
															stroke-width="2"
															stroke-dasharray="0"
															class="apexcharts-area"
															index="0"
															clip-path="url(#gridRectMasklqxyiohfg)"
															pathTo="M 0 173.5124441443549C 54.55818767914405 173.5124441443549 101.3223485469818 147.0444441901313 155.88053622612586 147.0444441901313C 192.25266134555523 147.0444441901313 223.4287685907804 182.3351107957628 259.8008937102098 182.3351107957628C 296.17301882963915 182.3351107957628 327.3491260748643 114.69466646830242 363.72125119429364 114.69466646830242C 400.093376313723 114.69466646830242 431.2694835589482 141.16266642252606 467.64160867837757 141.16266642252606C 504.01373379780694 141.16266642252606 535.1898410430321 23.52711107042103 571.5619661624614 23.52711107042103C 607.9340912818908 23.52711107042103 639.110198527116 99.99022204928929 675.4823236465454 99.99022204928929"
															pathFrom="M 0 264.6799995422363 L 0 264.6799995422363 L 155.88053622612586 264.6799995422363 L 259.8008937102098 264.6799995422363 L 363.72125119429364 264.6799995422363 L 467.64160867837757 264.6799995422363 L 571.5619661624614 264.6799995422363 L 675.4823236465454 264.6799995422363"
															fill-rule="evenodd"
														></path><g
															id="SvgjsG2305"
															class="apexcharts-series-markers-wrap apexcharts-hidden-element-shown"
															data:realIndex="0"
															><g
																id="SvgjsG2307"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2308"
																	d="M 0, 173.5124441443549 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#4154f1"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="0"
																	cy="173.5124441443549"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events wbondocnz"
																	rel="0"
																	j="0"
																	index="0"
																	default-marker-size="4"
																></path><path
																	id="SvgjsPath2309"
																	d="M 155.88053622612586, 147.0444441901313 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#4154f1"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="155.88053622612586"
																	cy="147.0444441901313"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events w60540r6a"
																	rel="1"
																	j="1"
																	index="0"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2310"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2311"
																	d="M 259.8008937102098, 182.3351107957628 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#4154f1"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="259.8008937102098"
																	cy="182.3351107957628"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events w5dqoaxy5"
																	rel="2"
																	j="2"
																	index="0"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2312"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2313"
																	d="M 363.72125119429364, 114.69466646830242 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#4154f1"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="363.72125119429364"
																	cy="114.69466646830242"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events w2vw92x9r"
																	rel="3"
																	j="3"
																	index="0"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2314"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2315"
																	d="M 467.64160867837757, 141.16266642252606 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#4154f1"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="467.64160867837757"
																	cy="141.16266642252606"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events wiwoxzjfn"
																	rel="4"
																	j="4"
																	index="0"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2316"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2317"
																	d="M 571.5619661624614, 23.52711107042103 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#4154f1"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="571.5619661624614"
																	cy="23.52711107042103"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events wtansirfy"
																	rel="5"
																	j="5"
																	index="0"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2318"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2319"
																	d="M 675.4823236465454, 99.99022204928929 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#4154f1"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="675.4823236465454"
																	cy="99.99022204928929"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events wm6ha84eb"
																	rel="6"
																	j="6"
																	index="0"
																	default-marker-size="4"
																></path></g
															></g
														></g
													><g
														id="SvgjsG2326"
														class="apexcharts-series"
														zIndex="1"
														seriesName="Revenue"
														data:longestSeries="true"
														rel="2"
														data:realIndex="1"
														><path
															id="SvgjsPath2346"
															d="M 0 232.33022182040744C 54.55818767914405 232.33022182040744 101.3223485469818 170.57155526055232 155.88053622612586 170.57155526055232C 192.25266134555523 170.57155526055232 223.4287685907804 132.33999977111816 259.8008937102098 132.33999977111816C 296.17301882963915 132.33999977111816 327.3491260748643 170.57155526055232 363.72125119429364 170.57155526055232C 400.093376313723 170.57155526055232 431.2694835589482 164.68977749294703 467.64160867837757 164.68977749294703C 504.01373379780694 164.68977749294703 535.1898410430321 111.75377758449977 571.5619661624614 111.75377758449977C 607.9340912818908 111.75377758449977 639.110198527116 144.10355530632867 675.4823236465454 144.10355530632867C 675.4823236465454 144.10355530632867 675.4823236465454 144.10355530632867 675.4823236465454 264.6799995422363 L 0 264.6799995422363z"
															fill="url(#SvgjsLinearGradient2342)"
															fill-opacity="1"
															stroke-opacity="1"
															stroke-linecap="butt"
															stroke-width="0"
															stroke-dasharray="0"
															class="apexcharts-area"
															index="1"
															clip-path="url(#gridRectMasklqxyiohfg)"
															pathTo="M 0 232.33022182040744C 54.55818767914405 232.33022182040744 101.3223485469818 170.57155526055232 155.88053622612586 170.57155526055232C 192.25266134555523 170.57155526055232 223.4287685907804 132.33999977111816 259.8008937102098 132.33999977111816C 296.17301882963915 132.33999977111816 327.3491260748643 170.57155526055232 363.72125119429364 170.57155526055232C 400.093376313723 170.57155526055232 431.2694835589482 164.68977749294703 467.64160867837757 164.68977749294703C 504.01373379780694 164.68977749294703 535.1898410430321 111.75377758449977 571.5619661624614 111.75377758449977C 607.9340912818908 111.75377758449977 639.110198527116 144.10355530632867 675.4823236465454 144.10355530632867C 675.4823236465454 144.10355530632867 675.4823236465454 144.10355530632867 675.4823236465454 264.6799995422363 L 0 264.6799995422363z"
															pathFrom="M 0 264.6799995422363 L 0 264.6799995422363 L 155.88053622612586 264.6799995422363 L 259.8008937102098 264.6799995422363 L 363.72125119429364 264.6799995422363 L 467.64160867837757 264.6799995422363 L 571.5619661624614 264.6799995422363 L 675.4823236465454 264.6799995422363z"
														></path><path
															id="SvgjsPath2347"
															d="M 0 232.33022182040744C 54.55818767914405 232.33022182040744 101.3223485469818 170.57155526055232 155.88053622612586 170.57155526055232C 192.25266134555523 170.57155526055232 223.4287685907804 132.33999977111816 259.8008937102098 132.33999977111816C 296.17301882963915 132.33999977111816 327.3491260748643 170.57155526055232 363.72125119429364 170.57155526055232C 400.093376313723 170.57155526055232 431.2694835589482 164.68977749294703 467.64160867837757 164.68977749294703C 504.01373379780694 164.68977749294703 535.1898410430321 111.75377758449977 571.5619661624614 111.75377758449977C 607.9340912818908 111.75377758449977 639.110198527116 144.10355530632867 675.4823236465454 144.10355530632867"
															fill="none"
															fill-opacity="1"
															stroke="#2eca6a"
															stroke-opacity="1"
															stroke-linecap="butt"
															stroke-width="2"
															stroke-dasharray="0"
															class="apexcharts-area"
															index="1"
															clip-path="url(#gridRectMasklqxyiohfg)"
															pathTo="M 0 232.33022182040744C 54.55818767914405 232.33022182040744 101.3223485469818 170.57155526055232 155.88053622612586 170.57155526055232C 192.25266134555523 170.57155526055232 223.4287685907804 132.33999977111816 259.8008937102098 132.33999977111816C 296.17301882963915 132.33999977111816 327.3491260748643 170.57155526055232 363.72125119429364 170.57155526055232C 400.093376313723 170.57155526055232 431.2694835589482 164.68977749294703 467.64160867837757 164.68977749294703C 504.01373379780694 164.68977749294703 535.1898410430321 111.75377758449977 571.5619661624614 111.75377758449977C 607.9340912818908 111.75377758449977 639.110198527116 144.10355530632867 675.4823236465454 144.10355530632867"
															pathFrom="M 0 264.6799995422363 L 0 264.6799995422363 L 155.88053622612586 264.6799995422363 L 259.8008937102098 264.6799995422363 L 363.72125119429364 264.6799995422363 L 467.64160867837757 264.6799995422363 L 571.5619661624614 264.6799995422363 L 675.4823236465454 264.6799995422363"
															fill-rule="evenodd"
														></path><g
															id="SvgjsG2327"
															class="apexcharts-series-markers-wrap apexcharts-hidden-element-shown"
															data:realIndex="1"
															><g
																id="SvgjsG2329"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2330"
																	d="M 0, 232.33022182040744 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#2eca6a"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="0"
																	cy="232.33022182040744"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events w3mfnuu47"
																	rel="0"
																	j="0"
																	index="1"
																	default-marker-size="4"
																></path><path
																	id="SvgjsPath2331"
																	d="M 155.88053622612586, 170.57155526055232 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#2eca6a"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="155.88053622612586"
																	cy="170.57155526055232"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events wnxgbff55"
																	rel="1"
																	j="1"
																	index="1"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2332"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2333"
																	d="M 259.8008937102098, 132.33999977111816 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#2eca6a"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="259.8008937102098"
																	cy="132.33999977111816"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events w2ff43vh8j"
																	rel="2"
																	j="2"
																	index="1"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2334"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2335"
																	d="M 363.72125119429364, 170.57155526055232 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#2eca6a"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="363.72125119429364"
																	cy="170.57155526055232"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events wgaffrimx"
																	rel="3"
																	j="3"
																	index="1"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2336"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2337"
																	d="M 467.64160867837757, 164.68977749294703 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#2eca6a"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="467.64160867837757"
																	cy="164.68977749294703"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events wuducjkoa"
																	rel="4"
																	j="4"
																	index="1"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2338"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2339"
																	d="M 571.5619661624614, 111.75377758449977 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#2eca6a"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="571.5619661624614"
																	cy="111.75377758449977"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events whl6u6ntql"
																	rel="5"
																	j="5"
																	index="1"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2340"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2341"
																	d="M 675.4823236465454, 144.10355530632867 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#2eca6a"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="675.4823236465454"
																	cy="144.10355530632867"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events wbgdjy0c7"
																	rel="6"
																	j="6"
																	index="1"
																	default-marker-size="4"
																></path></g
															></g
														></g
													><g
														id="SvgjsG2348"
														class="apexcharts-series"
														zIndex="2"
														seriesName="Customers"
														data:longestSeries="true"
														rel="3"
														data:realIndex="2"
														><path
															id="SvgjsPath2368"
															d="M 0 220.56666628519693C 54.55818767914405 220.56666628519693 101.3223485469818 232.33022182040744 155.88053622612586 232.33022182040744C 192.25266134555523 232.33022182040744 223.4287685907804 170.57155526055232 259.8008937102098 170.57155526055232C 296.17301882963915 170.57155526055232 327.3491260748643 211.74399963378906 363.72125119429364 211.74399963378906C 400.093376313723 211.74399963378906 431.2694835589482 238.2119995880127 467.64160867837757 238.2119995880127C 504.01373379780694 238.2119995880127 535.1898410430321 194.0986663309733 571.5619661624614 194.0986663309733C 607.9340912818908 194.0986663309733 639.110198527116 232.33022182040744 675.4823236465454 232.33022182040744C 675.4823236465454 232.33022182040744 675.4823236465454 232.33022182040744 675.4823236465454 264.6799995422363 L 0 264.6799995422363z"
															fill="url(#SvgjsLinearGradient2364)"
															fill-opacity="1"
															stroke-opacity="1"
															stroke-linecap="butt"
															stroke-width="0"
															stroke-dasharray="0"
															class="apexcharts-area"
															index="2"
															clip-path="url(#gridRectMasklqxyiohfg)"
															pathTo="M 0 220.56666628519693C 54.55818767914405 220.56666628519693 101.3223485469818 232.33022182040744 155.88053622612586 232.33022182040744C 192.25266134555523 232.33022182040744 223.4287685907804 170.57155526055232 259.8008937102098 170.57155526055232C 296.17301882963915 170.57155526055232 327.3491260748643 211.74399963378906 363.72125119429364 211.74399963378906C 400.093376313723 211.74399963378906 431.2694835589482 238.2119995880127 467.64160867837757 238.2119995880127C 504.01373379780694 238.2119995880127 535.1898410430321 194.0986663309733 571.5619661624614 194.0986663309733C 607.9340912818908 194.0986663309733 639.110198527116 232.33022182040744 675.4823236465454 232.33022182040744C 675.4823236465454 232.33022182040744 675.4823236465454 232.33022182040744 675.4823236465454 264.6799995422363 L 0 264.6799995422363z"
															pathFrom="M 0 264.6799995422363 L 0 264.6799995422363 L 155.88053622612586 264.6799995422363 L 259.8008937102098 264.6799995422363 L 363.72125119429364 264.6799995422363 L 467.64160867837757 264.6799995422363 L 571.5619661624614 264.6799995422363 L 675.4823236465454 264.6799995422363z"
														></path><path
															id="SvgjsPath2369"
															d="M 0 220.56666628519693C 54.55818767914405 220.56666628519693 101.3223485469818 232.33022182040744 155.88053622612586 232.33022182040744C 192.25266134555523 232.33022182040744 223.4287685907804 170.57155526055232 259.8008937102098 170.57155526055232C 296.17301882963915 170.57155526055232 327.3491260748643 211.74399963378906 363.72125119429364 211.74399963378906C 400.093376313723 211.74399963378906 431.2694835589482 238.2119995880127 467.64160867837757 238.2119995880127C 504.01373379780694 238.2119995880127 535.1898410430321 194.0986663309733 571.5619661624614 194.0986663309733C 607.9340912818908 194.0986663309733 639.110198527116 232.33022182040744 675.4823236465454 232.33022182040744"
															fill="none"
															fill-opacity="1"
															stroke="#ff771d"
															stroke-opacity="1"
															stroke-linecap="butt"
															stroke-width="2"
															stroke-dasharray="0"
															class="apexcharts-area"
															index="2"
															clip-path="url(#gridRectMasklqxyiohfg)"
															pathTo="M 0 220.56666628519693C 54.55818767914405 220.56666628519693 101.3223485469818 232.33022182040744 155.88053622612586 232.33022182040744C 192.25266134555523 232.33022182040744 223.4287685907804 170.57155526055232 259.8008937102098 170.57155526055232C 296.17301882963915 170.57155526055232 327.3491260748643 211.74399963378906 363.72125119429364 211.74399963378906C 400.093376313723 211.74399963378906 431.2694835589482 238.2119995880127 467.64160867837757 238.2119995880127C 504.01373379780694 238.2119995880127 535.1898410430321 194.0986663309733 571.5619661624614 194.0986663309733C 607.9340912818908 194.0986663309733 639.110198527116 232.33022182040744 675.4823236465454 232.33022182040744"
															pathFrom="M 0 264.6799995422363 L 0 264.6799995422363 L 155.88053622612586 264.6799995422363 L 259.8008937102098 264.6799995422363 L 363.72125119429364 264.6799995422363 L 467.64160867837757 264.6799995422363 L 571.5619661624614 264.6799995422363 L 675.4823236465454 264.6799995422363"
															fill-rule="evenodd"
														></path><g
															id="SvgjsG2349"
															class="apexcharts-series-markers-wrap apexcharts-hidden-element-shown"
															data:realIndex="2"
															><g
																id="SvgjsG2351"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2352"
																	d="M 0, 220.56666628519693 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#ff771d"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="0"
																	cy="220.56666628519693"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events w5mzorwfdj"
																	rel="0"
																	j="0"
																	index="2"
																	default-marker-size="4"
																></path><path
																	id="SvgjsPath2353"
																	d="M 155.88053622612586, 232.33022182040744 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#ff771d"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="155.88053622612586"
																	cy="232.33022182040744"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events whg0fpdrvk"
																	rel="1"
																	j="1"
																	index="2"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2354"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2355"
																	d="M 259.8008937102098, 170.57155526055232 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#ff771d"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="259.8008937102098"
																	cy="170.57155526055232"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events w60e99vfe"
																	rel="2"
																	j="2"
																	index="2"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2356"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2357"
																	d="M 363.72125119429364, 211.74399963378906 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#ff771d"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="363.72125119429364"
																	cy="211.74399963378906"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events wjasm61zq"
																	rel="3"
																	j="3"
																	index="2"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2358"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2359"
																	d="M 467.64160867837757, 238.2119995880127 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#ff771d"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="467.64160867837757"
																	cy="238.2119995880127"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events wg8nskljy"
																	rel="4"
																	j="4"
																	index="2"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2360"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2361"
																	d="M 571.5619661624614, 194.0986663309733 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#ff771d"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="571.5619661624614"
																	cy="194.0986663309733"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events w3ppj50pe"
																	rel="5"
																	j="5"
																	index="2"
																	default-marker-size="4"
																></path></g
															><g
																id="SvgjsG2362"
																class="apexcharts-series-markers"
																clip-path="url(#gridRectMarkerMasklqxyiohfg)"
																><path
																	id="SvgjsPath2363"
																	d="M 675.4823236465454, 232.33022182040744 
           m -4, 0 
           a 4,4 0 1,0 8,0 
           a 4,4 0 1,0 -8,0"
																	fill="#ff771d"
																	fill-opacity="1"
																	stroke="#ffffff"
																	stroke-opacity="0.9"
																	stroke-linecap="butt"
																	stroke-width="2"
																	stroke-dasharray="0"
																	cx="675.4823236465454"
																	cy="232.33022182040744"
																	shape="circle"
																	class="apexcharts-marker no-pointer-events wphwcndhy"
																	rel="6"
																	j="6"
																	index="2"
																	default-marker-size="4"
																></path></g
															></g
														></g
													><g id="SvgjsG2306" class="apexcharts-datalabels" data:realIndex="0"
													></g><g id="SvgjsG2328" class="apexcharts-datalabels" data:realIndex="1"
													></g><g id="SvgjsG2350" class="apexcharts-datalabels" data:realIndex="2"
													></g></g
												><line
													id="SvgjsLine2393"
													x1="0"
													y1="0"
													x2="675.4823236465454"
													y2="0"
													stroke="#b6b6b6"
													stroke-dasharray="0"
													stroke-width="1"
													stroke-linecap="butt"
													class="apexcharts-ycrosshairs"
												></line><line
													id="SvgjsLine2394"
													x1="0"
													y1="0"
													x2="675.4823236465454"
													y2="0"
													stroke-dasharray="0"
													stroke-width="0"
													stroke-linecap="butt"
													class="apexcharts-ycrosshairs-hidden"
												></line><g
													id="SvgjsG2395"
													class="apexcharts-xaxis"
													transform="translate(0, 0)"
													><g
														id="SvgjsG2396"
														class="apexcharts-xaxis-texts-g"
														transform="translate(0, -4)"
														><text
															id="SvgjsText2398"
															font-family="Helvetica, Arial, sans-serif"
															x="0"
															y="292.6799995422363"
															text-anchor="middle"
															dominant-baseline="auto"
															font-size="12px"
															font-weight="400"
															fill="#373d3f"
															class="apexcharts-text apexcharts-xaxis-label"
															style="font-family: Helvetica, Arial, sans-serif;"
															><tspan id="SvgjsTspan2399">00:00</tspan><title>00:00</title></text
														><text
															id="SvgjsText2401"
															font-family="Helvetica, Arial, sans-serif"
															x="103.92035748408392"
															y="292.6799995422363"
															text-anchor="middle"
															dominant-baseline="auto"
															font-size="12px"
															font-weight="400"
															fill="#373d3f"
															class="apexcharts-text apexcharts-xaxis-label"
															style="font-family: Helvetica, Arial, sans-serif;"
															><tspan id="SvgjsTspan2402">01:00</tspan><title>01:00</title></text
														><text
															id="SvgjsText2404"
															font-family="Helvetica, Arial, sans-serif"
															x="207.84071496816784"
															y="292.6799995422363"
															text-anchor="middle"
															dominant-baseline="auto"
															font-size="12px"
															font-weight="400"
															fill="#373d3f"
															class="apexcharts-text apexcharts-xaxis-label"
															style="font-family: Helvetica, Arial, sans-serif;"
															><tspan id="SvgjsTspan2405">02:00</tspan><title>02:00</title></text
														><text
															id="SvgjsText2407"
															font-family="Helvetica, Arial, sans-serif"
															x="311.76107245225177"
															y="292.6799995422363"
															text-anchor="middle"
															dominant-baseline="auto"
															font-size="12px"
															font-weight="400"
															fill="#373d3f"
															class="apexcharts-text apexcharts-xaxis-label"
															style="font-family: Helvetica, Arial, sans-serif;"
															><tspan id="SvgjsTspan2408">03:00</tspan><title>03:00</title></text
														><text
															id="SvgjsText2410"
															font-family="Helvetica, Arial, sans-serif"
															x="415.6814299363357"
															y="292.6799995422363"
															text-anchor="middle"
															dominant-baseline="auto"
															font-size="12px"
															font-weight="400"
															fill="#373d3f"
															class="apexcharts-text apexcharts-xaxis-label"
															style="font-family: Helvetica, Arial, sans-serif;"
															><tspan id="SvgjsTspan2411">04:00</tspan><title>04:00</title></text
														><text
															id="SvgjsText2413"
															font-family="Helvetica, Arial, sans-serif"
															x="519.6017874204197"
															y="292.6799995422363"
															text-anchor="middle"
															dominant-baseline="auto"
															font-size="12px"
															font-weight="400"
															fill="#373d3f"
															class="apexcharts-text apexcharts-xaxis-label"
															style="font-family: Helvetica, Arial, sans-serif;"
															><tspan id="SvgjsTspan2414">05:00</tspan><title>05:00</title></text
														><text
															id="SvgjsText2416"
															font-family="Helvetica, Arial, sans-serif"
															x="623.5221449045036"
															y="292.6799995422363"
															text-anchor="middle"
															dominant-baseline="auto"
															font-size="12px"
															font-weight="400"
															fill="#373d3f"
															class="apexcharts-text apexcharts-xaxis-label"
															style="font-family: Helvetica, Arial, sans-serif;"
															><tspan id="SvgjsTspan2417">06:00</tspan><title>06:00</title></text
														></g
													></g
												><g id="SvgjsG2451" class="apexcharts-yaxis-annotations"></g><g
													id="SvgjsG2452"
													class="apexcharts-xaxis-annotations"
												></g><g id="SvgjsG2453" class="apexcharts-point-annotations"></g><rect
													id="SvgjsRect2454"
													width="0"
													height="0"
													x="0"
													y="0"
													rx="0"
													ry="0"
													opacity="1"
													stroke-width="0"
													stroke="none"
													stroke-dasharray="0"
													fill="#fefefe"
													class="apexcharts-zoom-rect"
												></rect><rect
													id="SvgjsRect2455"
													width="0"
													height="0"
													x="0"
													y="0"
													rx="0"
													ry="0"
													opacity="1"
													stroke-width="0"
													stroke="none"
													stroke-dasharray="0"
													fill="#fefefe"
													class="apexcharts-selection-rect"
												></rect></g
											></svg
										>
										<div class="apexcharts-tooltip apexcharts-theme-light">
											<div
												class="apexcharts-tooltip-title"
												style="font-family: Helvetica, Arial, sans-serif; font-size: 12px;"
											></div>
											<div class="apexcharts-tooltip-series-group" style="order: 1;">
												<span
													class="apexcharts-tooltip-marker"
													style="background-color: rgb(65, 84, 241);"
												></span>
												<div
													class="apexcharts-tooltip-text"
													style="font-family: Helvetica, Arial, sans-serif; font-size: 12px;"
												>
													<div class="apexcharts-tooltip-y-group">
														<span class="apexcharts-tooltip-text-y-label"></span><span
															class="apexcharts-tooltip-text-y-value"
														></span>
													</div>
													<div class="apexcharts-tooltip-goals-group">
														<span class="apexcharts-tooltip-text-goals-label"></span><span
															class="apexcharts-tooltip-text-goals-value"
														></span>
													</div>
													<div class="apexcharts-tooltip-z-group">
														<span class="apexcharts-tooltip-text-z-label"></span><span
															class="apexcharts-tooltip-text-z-value"
														></span>
													</div>
												</div>
											</div>
											<div class="apexcharts-tooltip-series-group" style="order: 2;">
												<span
													class="apexcharts-tooltip-marker"
													style="background-color: rgb(46, 202, 106);"
												></span>
												<div
													class="apexcharts-tooltip-text"
													style="font-family: Helvetica, Arial, sans-serif; font-size: 12px;"
												>
													<div class="apexcharts-tooltip-y-group">
														<span class="apexcharts-tooltip-text-y-label"></span><span
															class="apexcharts-tooltip-text-y-value"
														></span>
													</div>
													<div class="apexcharts-tooltip-goals-group">
														<span class="apexcharts-tooltip-text-goals-label"></span><span
															class="apexcharts-tooltip-text-goals-value"
														></span>
													</div>
													<div class="apexcharts-tooltip-z-group">
														<span class="apexcharts-tooltip-text-z-label"></span><span
															class="apexcharts-tooltip-text-z-value"
														></span>
													</div>
												</div>
											</div>
											<div class="apexcharts-tooltip-series-group" style="order: 3;">
												<span
													class="apexcharts-tooltip-marker"
													style="background-color: rgb(255, 119, 29);"
												></span>
												<div
													class="apexcharts-tooltip-text"
													style="font-family: Helvetica, Arial, sans-serif; font-size: 12px;"
												>
													<div class="apexcharts-tooltip-y-group">
														<span class="apexcharts-tooltip-text-y-label"></span><span
															class="apexcharts-tooltip-text-y-value"
														></span>
													</div>
													<div class="apexcharts-tooltip-goals-group">
														<span class="apexcharts-tooltip-text-goals-label"></span><span
															class="apexcharts-tooltip-text-goals-value"
														></span>
													</div>
													<div class="apexcharts-tooltip-z-group">
														<span class="apexcharts-tooltip-text-z-label"></span><span
															class="apexcharts-tooltip-text-z-value"
														></span>
													</div>
												</div>
											</div>
										</div>
										<div
											class="apexcharts-xaxistooltip apexcharts-xaxistooltip-bottom apexcharts-theme-light"
										>
											<div
												class="apexcharts-xaxistooltip-text"
												style="font-family: Helvetica, Arial, sans-serif; font-size: 12px;"
											></div>
										</div>
										<div
											class="apexcharts-yaxistooltip apexcharts-yaxistooltip-0 apexcharts-yaxistooltip-left apexcharts-theme-light"
										>
											<div class="apexcharts-yaxistooltip-text"></div>
										</div>
									</div>
								</div>

								<script>
									document.addEventListener('DOMContentLoaded', () => {
										new ApexCharts(document.querySelector('#reportsChart'), {
											series: [
												{
													name: 'Sales',
													data: [31, 40, 28, 51, 42, 82, 56]
												},
												{
													name: 'Revenue',
													data: [11, 32, 45, 32, 34, 52, 41]
												},
												{
													name: 'Customers',
													data: [15, 11, 32, 18, 9, 24, 11]
												}
											],
											chart: {
												height: 350,
												type: 'area',
												toolbar: {
													show: false
												}
											},
											markers: {
												size: 4
											},
											colors: ['#4154f1', '#2eca6a', '#ff771d'],
											fill: {
												type: 'gradient',
												gradient: {
													shadeIntensity: 1,
													opacityFrom: 0.3,
													opacityTo: 0.4,
													stops: [0, 90, 100]
												}
											},
											dataLabels: {
												enabled: false
											},
											stroke: {
												curve: 'smooth',
												width: 2
											},
											xaxis: {
												type: 'datetime',
												categories: [
													'2018-09-19T00:00:00.000Z',
													'2018-09-19T01:30:00.000Z',
													'2018-09-19T02:30:00.000Z',
													'2018-09-19T03:30:00.000Z',
													'2018-09-19T04:30:00.000Z',
													'2018-09-19T05:30:00.000Z',
													'2018-09-19T06:30:00.000Z'
												]
											},
											tooltip: {
												x: {
													format: 'dd/MM/yy HH:mm'
												}
											}
										}).render();
									});
								</script>
								<!-- End Line Chart -->
							</div>
						</div>
					</div>
					<!-- End Reports -->

					<!-- Recent Sales -->
					<div class="col-12">
						<div class="card recent-sales overflow-auto">
							<div class="filter">
								<a class="icon" href="#" data-bs-toggle="dropdown"
									><i class="bi bi-three-dots"></i></a
								>
								<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow">
									<li class="dropdown-header text-start">
										<h6>Filter</h6>
									</li>

									<li><a class="dropdown-item" href="#">Today</a></li>
									<li><a class="dropdown-item" href="#">This Month</a></li>
									<li><a class="dropdown-item" href="#">This Year</a></li>
								</ul>
							</div>

							<div class="card-body">
								<h5 class="card-title">Recent Sales <span>| Today</span></h5>

								<div
									class="datatable-wrapper datatable-loading no-footer sortable searchable fixed-columns"
								>
									<div class="datatable-top">
										<div class="datatable-dropdown">
											<label>
												<select class="datatable-selector" name="per-page"
													><option value="5">5</option><option value="10" selected="">10</option
													><option value="15">15</option><option value="-1">All</option></select
												> entries per page
											</label>
										</div>
										<div class="datatable-search">
											<input
												class="datatable-input"
												placeholder="Search..."
												type="search"
												name="search"
												title="Search within table"
											/>
										</div>
									</div>
									<div class="datatable-container">
										<table class="table-borderless datatable datatable-table table">
											<thead
												><tr
													><th scope="col" data-sortable="true" style="width: 10.660980810234541%;"
														><button class="datatable-sorter">#</button></th
													><th scope="col" data-sortable="true" style="width: 23.454157782515992%;"
														><button class="datatable-sorter">Customer</button></th
													><th scope="col" data-sortable="true" style="width: 39.33901918976546%;"
														><button class="datatable-sorter">Product</button></th
													><th scope="col" data-sortable="true" style="width: 11.727078891257996%;"
														><button class="datatable-sorter">Price</button></th
													><th
														scope="col"
														data-sortable="true"
														class="red"
														style="width: 14.818763326226012%;"
														><button class="datatable-sorter">Status</button></th
													></tr
												></thead
											><tbody
												><tr data-index="0"
													><td scope="row"><a href="#">#2457</a></td><td>Brandon Jacob</td><td
														><a href="#" class="text-primary">At praesentium minu</a></td
													><td>$64</td><td class="green"
														><span class="badge bg-success">Approved</span></td
													></tr
												><tr data-index="1"
													><td scope="row"><a href="#">#2147</a></td><td>Bridie Kessler</td><td
														><a href="#" class="text-primary">Blanditiis dolor omnis similique</a
														></td
													><td>$47</td><td class="green"
														><span class="badge bg-warning">Pending</span></td
													></tr
												><tr data-index="2"
													><td scope="row"><a href="#">#2049</a></td><td>Ashleigh Langosh</td><td
														><a href="#" class="text-primary">At recusandae consectetur</a></td
													><td>$147</td><td class="green"
														><span class="badge bg-success">Approved</span></td
													></tr
												><tr data-index="3"
													><td scope="row"><a href="#">#2644</a></td><td>Angus Grady</td><td
														><a href="#" class="text-primar">Ut voluptatem id earum et</a></td
													><td>$67</td><td class="green"
														><span class="badge bg-danger">Rejected</span></td
													></tr
												><tr data-index="4"
													><td scope="row"><a href="#">#2644</a></td><td>Raheem Lehner</td><td
														><a href="#" class="text-primary">Sunt similique distinctio</a></td
													><td>$165</td><td class="green"
														><span class="badge bg-success">Approved</span></td
													></tr
												></tbody
											>
										</table>
									</div>
									<div class="datatable-bottom">
										<div class="datatable-info">Showing 1 to 5 of 5 entries</div>
										<nav class="datatable-pagination">
											<ul class="datatable-pagination-list"></ul>
										</nav>
									</div>
								</div>
							</div>
						</div>
					</div>
					<!-- End Recent Sales -->

					<!-- Top Selling -->
					<div class="col-12">
						<div class="card top-selling overflow-auto">
							<div class="filter">
								<a class="icon" href="#" data-bs-toggle="dropdown"
									><i class="bi bi-three-dots"></i></a
								>
								<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow">
									<li class="dropdown-header text-start">
										<h6>Filter</h6>
									</li>

									<li><a class="dropdown-item" href="#">Today</a></li>
									<li><a class="dropdown-item" href="#">This Month</a></li>
									<li><a class="dropdown-item" href="#">This Year</a></li>
								</ul>
							</div>

							<div class="card-body pb-0">
								<h5 class="card-title">Top Selling <span>| Today</span></h5>

								<table class="table-borderless table">
									<thead>
										<tr>
											<th scope="col">Preview</th>
											<th scope="col">Product</th>
											<th scope="col">Price</th>
											<th scope="col">Sold</th>
											<th scope="col">Revenue</th>
										</tr>
									</thead>
									<tbody>
										<tr>
											<th scope="row"
												><a href="#"><img src="assets/img/product-1.jpg" alt="" /></a></th
											>
											<td
												><a href="#" class="text-primary fw-bold"
													>Ut inventore ipsa voluptas nulla</a
												></td
											>
											<td>$64</td>
											<td class="fw-bold">124</td>
											<td>$5,828</td>
										</tr>
										<tr>
											<th scope="row"
												><a href="#"><img src="assets/img/product-2.jpg" alt="" /></a></th
											>
											<td
												><a href="#" class="text-primary fw-bold"
													>Exercitationem similique doloremque</a
												></td
											>
											<td>$46</td>
											<td class="fw-bold">98</td>
											<td>$4,508</td>
										</tr>
										<tr>
											<th scope="row"
												><a href="#"><img src="assets/img/product-3.jpg" alt="" /></a></th
											>
											<td
												><a href="#" class="text-primary fw-bold">Doloribus nisi exercitationem</a
												></td
											>
											<td>$59</td>
											<td class="fw-bold">74</td>
											<td>$4,366</td>
										</tr>
										<tr>
											<th scope="row"
												><a href="#"><img src="assets/img/product-4.jpg" alt="" /></a></th
											>
											<td
												><a href="#" class="text-primary fw-bold"
													>Officiis quaerat sint rerum error</a
												></td
											>
											<td>$32</td>
											<td class="fw-bold">63</td>
											<td>$2,016</td>
										</tr>
										<tr>
											<th scope="row"
												><a href="#"><img src="assets/img/product-5.jpg" alt="" /></a></th
											>
											<td
												><a href="#" class="text-primary fw-bold"
													>Sit unde debitis delectus repellendus</a
												></td
											>
											<td>$79</td>
											<td class="fw-bold">41</td>
											<td>$3,239</td>
										</tr>
									</tbody>
								</table>
							</div>
						</div>
					</div>
					<!-- End Top Selling -->
				</div>
			</div>
			<!-- End Left side columns -->

			<!-- Right side columns -->
			<div class="col-lg-4">
				<!-- Recent Activity -->
				<div class="card">
					<div class="filter">
						<a class="icon" href="#" data-bs-toggle="dropdown"><i class="bi bi-three-dots"></i></a>
						<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow">
							<li class="dropdown-header text-start">
								<h6>Filter</h6>
							</li>

							<li><a class="dropdown-item" href="#">Today</a></li>
							<li><a class="dropdown-item" href="#">This Month</a></li>
							<li><a class="dropdown-item" href="#">This Year</a></li>
						</ul>
					</div>

					<div class="card-body">
						<h5 class="card-title">Recent Activity <span>| Today</span></h5>

						<div class="activity">
							<div class="activity-item d-flex">
								<div class="activite-label">32 min</div>
								<i class="bi bi-circle-fill activity-badge text-success align-self-start"></i>
								<div class="activity-content">
									Quia quae rerum <a href="#" class="fw-bold text-dark">explicabo officiis</a> beatae
								</div>
							</div>
							<!-- End activity item-->

							<div class="activity-item d-flex">
								<div class="activite-label">56 min</div>
								<i class="bi bi-circle-fill activity-badge text-danger align-self-start"></i>
								<div class="activity-content">Voluptatem blanditiis blanditiis eveniet</div>
							</div>
							<!-- End activity item-->

							<div class="activity-item d-flex">
								<div class="activite-label">2 hrs</div>
								<i class="bi bi-circle-fill activity-badge text-primary align-self-start"></i>
								<div class="activity-content">Voluptates corrupti molestias voluptatem</div>
							</div>
							<!-- End activity item-->

							<div class="activity-item d-flex">
								<div class="activite-label">1 day</div>
								<i class="bi bi-circle-fill activity-badge text-info align-self-start"></i>
								<div class="activity-content">
									Tempore autem saepe <a href="#" class="fw-bold text-dark">occaecati voluptatem</a>
									tempore
								</div>
							</div>
							<!-- End activity item-->

							<div class="activity-item d-flex">
								<div class="activite-label">2 days</div>
								<i class="bi bi-circle-fill activity-badge text-warning align-self-start"></i>
								<div class="activity-content">Est sit eum reiciendis exercitationem</div>
							</div>
							<!-- End activity item-->

							<div class="activity-item d-flex">
								<div class="activite-label">4 weeks</div>
								<i class="bi bi-circle-fill activity-badge text-muted align-self-start"></i>
								<div class="activity-content">
									Dicta dolorem harum nulla eius. Ut quidem quidem sit quas
								</div>
							</div>
							<!-- End activity item-->
						</div>
					</div>
				</div>
				<!-- End Recent Activity -->

				<!-- Budget Report -->
				<div class="card">
					<div class="filter">
						<a class="icon" href="#" data-bs-toggle="dropdown"><i class="bi bi-three-dots"></i></a>
						<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow">
							<li class="dropdown-header text-start">
								<h6>Filter</h6>
							</li>

							<li><a class="dropdown-item" href="#">Today</a></li>
							<li><a class="dropdown-item" href="#">This Month</a></li>
							<li><a class="dropdown-item" href="#">This Year</a></li>
						</ul>
					</div>

					<div class="card-body pb-0">
						<h5 class="card-title">Budget Report <span>| This Month</span></h5>

						<div
							id="budgetChart"
							style="min-height: 400px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0);"
							class="echart"
							_echarts_instance_="ec_1730293382497"
						>
							<div
								style="position: relative; width: 330px; height: 400px; padding: 0px; margin: 0px; border-width: 0px;"
							>
								<canvas
									data-zr-dom-id="zr_0"
									width="412"
									height="500"
									style="position: absolute; left: 0px; top: 0px; width: 330px; height: 400px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); padding: 0px; margin: 0px; border-width: 0px;"
								></canvas>
							</div>
						</div>

						<script>
							document.addEventListener('DOMContentLoaded', () => {
								var budgetChart = echarts.init(document.querySelector('#budgetChart')).setOption({
									legend: {
										data: ['Allocated Budget', 'Actual Spending']
									},
									radar: {
										// shape: 'circle',
										indicator: [
											{
												name: 'Sales',
												max: 6500
											},
											{
												name: 'Administration',
												max: 16000
											},
											{
												name: 'Information Technology',
												max: 30000
											},
											{
												name: 'Customer Support',
												max: 38000
											},
											{
												name: 'Development',
												max: 52000
											},
											{
												name: 'Marketing',
												max: 25000
											}
										]
									},
									series: [
										{
											name: 'Budget vs spending',
											type: 'radar',
											data: [
												{
													value: [4200, 3000, 20000, 35000, 50000, 18000],
													name: 'Allocated Budget'
												},
												{
													value: [5000, 14000, 28000, 26000, 42000, 21000],
													name: 'Actual Spending'
												}
											]
										}
									]
								});
							});
						</script>
					</div>
				</div>
				<!-- End Budget Report -->

				<!-- Website Traffic -->
				<div class="card">
					<div class="filter">
						<a class="icon" href="#" data-bs-toggle="dropdown"><i class="bi bi-three-dots"></i></a>
						<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow">
							<li class="dropdown-header text-start">
								<h6>Filter</h6>
							</li>

							<li><a class="dropdown-item" href="#">Today</a></li>
							<li><a class="dropdown-item" href="#">This Month</a></li>
							<li><a class="dropdown-item" href="#">This Year</a></li>
						</ul>
					</div>

					<div class="card-body pb-0">
						<h5 class="card-title">Website Traffic <span>| Today</span></h5>

						<div
							id="trafficChart"
							style="min-height: 400px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); position: relative;"
							class="echart"
							_echarts_instance_="ec_1730293382498"
						>
							<div
								style="position: relative; width: 330px; height: 400px; padding: 0px; margin: 0px; border-width: 0px;"
							>
								<canvas
									data-zr-dom-id="zr_0"
									width="412"
									height="500"
									style="position: absolute; left: 0px; top: 0px; width: 330px; height: 400px; user-select: none; -webkit-tap-highlight-color: rgba(0, 0, 0, 0); padding: 0px; margin: 0px; border-width: 0px;"
								></canvas>
							</div>
							<div class=""></div>
						</div>

						<script>
							document.addEventListener('DOMContentLoaded', () => {
								echarts.init(document.querySelector('#trafficChart')).setOption({
									tooltip: {
										trigger: 'item'
									},
									legend: {
										top: '5%',
										left: 'center'
									},
									series: [
										{
											name: 'Access From',
											type: 'pie',
											radius: ['40%', '70%'],
											avoidLabelOverlap: false,
											label: {
												show: false,
												position: 'center'
											},
											emphasis: {
												label: {
													show: true,
													fontSize: '18',
													fontWeight: 'bold'
												}
											},
											labelLine: {
												show: false
											},
											data: [
												{
													value: 1048,
													name: 'Search Engine'
												},
												{
													value: 735,
													name: 'Direct'
												},
												{
													value: 580,
													name: 'Email'
												},
												{
													value: 484,
													name: 'Union Ads'
												},
												{
													value: 300,
													name: 'Video Ads'
												}
											]
										}
									]
								});
							});
						</script>
					</div>
				</div>
				<!-- End Website Traffic -->

				<!-- News & Updates Traffic -->
				<div class="card">
					<div class="filter">
						<a class="icon" href="#" data-bs-toggle="dropdown"><i class="bi bi-three-dots"></i></a>
						<ul class="dropdown-menu dropdown-menu-end dropdown-menu-arrow">
							<li class="dropdown-header text-start">
								<h6>Filter</h6>
							</li>

							<li><a class="dropdown-item" href="#">Today</a></li>
							<li><a class="dropdown-item" href="#">This Month</a></li>
							<li><a class="dropdown-item" href="#">This Year</a></li>
						</ul>
					</div>

					<div class="card-body pb-0">
						<h5 class="card-title">News &amp; Updates <span>| Today</span></h5>

						<div class="news">
							<div class="post-item clearfix">
								<img src="assets/img/news-1.jpg" alt="" />
								<h4><a href="#">Nihil blanditiis at in nihil autem</a></h4>
								<p>Sit recusandae non aspernatur laboriosam. Quia enim eligendi sed ut harum...</p>
							</div>

							<div class="post-item clearfix">
								<img src="assets/img/news-2.jpg" alt="" />
								<h4><a href="#">Quidem autem et impedit</a></h4>
								<p>
									Illo nemo neque maiores vitae officiis cum eum turos elan dries werona nande...
								</p>
							</div>

							<div class="post-item clearfix">
								<img src="assets/img/news-3.jpg" alt="" />
								<h4><a href="#">Id quia et et ut maxime similique occaecati ut</a></h4>
								<p>
									Fugiat voluptas vero eaque accusantium eos. Consequuntur sed ipsam et totam...
								</p>
							</div>

							<div class="post-item clearfix">
								<img src="assets/img/news-4.jpg" alt="" />
								<h4><a href="#">Laborum corporis quo dara net para</a></h4>
								<p>
									Qui enim quia optio. Eligendi aut asperiores enim repellendusvel rerum cuder...
								</p>
							</div>

							<div class="post-item clearfix">
								<img src="assets/img/news-5.jpg" alt="" />
								<h4><a href="#">Et dolores corrupti quae illo quod dolor</a></h4>
								<p>
									Odit ut eveniet modi reiciendis. Atque cupiditate libero beatae dignissimos
									eius...
								</p>
							</div>
						</div>
						<!-- End sidebar recent posts-->
					</div>
				</div>
				<!-- End News & Updates -->
			</div>
			<!-- End Right side columns -->
		</div>
	</section>
</main>
