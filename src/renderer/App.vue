<template>
	<div id="app" class="app">
		<div class="app-expander">
			<!-- START: Toolbar component -->
			<div class="toolbar-tray">
				<div class="toolbar">
					<div class="toolbar-item">
						<button>
							<svg class="icon-menu">
								<use xlink:href="static/icons.svg#icon-menu"></use>
							</svg>
						</button>
						<label>Categories</label>
					</div>
				</div>
			</div>
			<!-- ENDS: Toolbar component -->
		</div>

		<div class="app-header">
			<!-- START: Toolbar component -->
			<div class="toolbar-tray">
				<div class="toolbar">
					<div class="toolbar-item">
						<button>
							<svg class="icon-new">
								<use xlink:href="static/icons.svg#icon-new"></use>
							</svg>
						</button>
					</div>
					<div class="toolbar-item">
						<button>
							<svg class="icon-plus">
								<use xlink:href="static/icons.svg#icon-plus"></use>
							</svg>
						</button>
					</div>
					<div class="toolbar-item">
						<button>
							<svg class="icon-rss">
								<use xlink:href="static/icons.svg#icon-rss"></use>
							</svg>
						</button>
					</div>
					<div class="toolbar-item">
						<button>
							<svg class="icon-url">
								<use xlink:href="static/icons.svg#icon-url"></use>
							</svg>
						</button>
					</div>
					<div class="toolbar-item">
						<button>
							<svg class="icon-folder">
								<use xlink:href="static/icons.svg#icon-folder"></use>
							</svg>
						</button>
					</div>
				</div>
				<div class="separator vertical"></div>
				<div class="toolbar">
					<div class="toolbar-item">
						<button>
							<svg class="icon-start">
								<use xlink:href="static/icons.svg#icon-start"></use>
							</svg>
						</button>
					</div>
					<div class="toolbar-item">
						<button>
							<svg class="icon-pause">
								<use xlink:href="static/icons.svg#icon-pause"></use>
							</svg>
						</button>
					</div>
					<div class="toolbar-item">
						<button>
							<svg class="icon-stop">
								<use xlink:href="static/icons.svg#icon-stop"></use>
							</svg>
						</button>
					</div>
					<div class="toolbar-item">
						<button>
							<svg class="icon-cross">
								<use xlink:href="static/icons.svg#icon-cross"></use>
							</svg>
						</button>
					</div>
				</div>
				<div class="separator vertical"></div>
				<div class="toolbar stretch">
					<div class="toolbar-item stretch">
						<div class="search-box stretch">
							<input type="search" name="appsearch" placeholder="Search">
							<button>
								<!--<svg class="icon-search">-->
								<!--<use xlink:href="static/icons.svg#icon-search"></use>-->
								<!--</svg>-->
								<svg class="icon-cross">
									<use xlink:href="static/icons.svg#icon-cross"></use>
								</svg>
							</button>
						</div>
					</div>
					<div class="toolbar-item">
						<button>
							<svg class="icon-preferences">
								<use xlink:href="static/icons.svg#icon-preferences"></use>
							</svg>
						</button>
					</div>
				</div>
				<div class="separator vertical"></div>
				<div class="toolbar">
					<div class="toolbar-item">
						<div class="speedometer">
							<div class="speedometer-item">
								<div class="speedometer-title">Download</div>
								<div class="speedometer-content">
									<span class="speedometer-numbers">120.40</span>
									<span class="speedometer-units"><svg class="icon-down"><use
										xlink:href="static/icons.svg#icon-down"></use></svg>MB/s</span>
								</div>
							</div>
							<div class="speedometer-item">
								<div class="speedometer-title">Upload</div>
								<div class="speedometer-content">
									<span class="speedometer-numbers">120.40</span>
									<span class="speedometer-units"><svg class="icon-up"><use
										xlink:href="static/icons.svg#icon-up"></use></svg>MB/s</span>
								</div>
							</div>
						</div>
					</div>
					<div class="toolbar-item">
						<button class="active">
							<svg class="icon-speedometer">
								<use xlink:href="static/icons.svg#icon-speedometer"></use>
							</svg>
						</button>
					</div>
				</div>
			</div>
			<!-- ENDS: Toolbar component -->
		</div>

		<div class="app-sidebar">

			<div class="categories">
				<div class="categories-section">
					<div class="categories-section-title">Status</div>
					<div class="categories-section-list">
						<div class="categories-section-list-item">
							<span class="label">Downloading</span><span class="badge">12</span>
						</div>
						<div class="categories-section-list-item">
							<span class="label">Seeding</span><span class="badge">4</span>
						</div>
						<div class="categories-section-list-item">
							<span class="label">Completed</span><span class="badge">2</span>
						</div>
						<div class="categories-section-list-item">
							<span class="label">Meet rules</span><span class="badge">10</span>
						</div>
					</div>
				</div>

				<div class="categories-section">
					<div class="categories-section-title">Trackers</div>
					<div class="categories-section-list">
						<div class="categories-section-list-item">
							<span class="label">openbittorrenttracker.com</span><span class="badge">2</span>
						</div>
					</div>
				</div>

				<div class="categories-section">
					<div class="categories-section-title">RSS Feeds</div>
					<div class="categories-section-list">
						<div class="categories-section-list-item">
							<span class="label">Torrentday</span><span class="badge">2</span>
						</div>
					</div>
				</div>

				<div class="categories-section">
					<div class="categories-section-title">Tags</div>
					<div class="categories-section-list">
						<div class="categories-section-list-item">
							<span class="label">Movies</span><span class="badge">2</span>
						</div>
						<div class="categories-section-list-item">
							<span class="label">Series</span><span class="badge">2</span>
						</div>
					</div>
				</div>

			</div>
		</div>

		<div class="app-content">
			<table>
				<thead>
				<tr>
					<th>Name</th>
					<th>Size</th>
					<th>Percentage</th>
					<th>Availability</th>
					<th>Down Speed</th>
					<th>Up Speed</th>
					<th>Ratio</th>
					<th>Seeding Time</th>
					<th>ETA</th>
				</tr>
				</thead>
				<tbody>
				<tr>
					<td>
						<div class="primary-line">
							<svg class="icon-folder">
								<use xlink:href="static/icons.svg#icon-folder"></use>
							</svg>
							MAME Rom Collection 0.186 7z Non-merged
						</div>
						<div class="secondary-line">tracker.openbittorrent.com:80</div>
					</td>
					<td>
						<div class="primary-line">20.3 GB</div>
						<div class="secondary-line">2.1 GB done</div>
					</td>
					<td>
						<div class="primary-line">12%</div>
						<div class="secondary-line">Downloading</div>
					</td>
					<td>
						<div class="primary-line">18.685</div>
						<div class="secondary-line">18 seeds / 9 peers</div>
					</td>
					<td>
						<div class="primary-line">5.6 MB/s</div>
						<div class="secondary-line">from 18 peers</div>
					</td>
					<td>
						<div class="primary-line">89 KB/s</div>
						<div class="secondary-line">to 9 peers</div>
					</td>
					<td>
						<div class="primary-line warning">0.5</div>
						<div class="secondary-line">1.0 needed</div>
					</td>
					<td>
						<div class="primary-line warning">1h 25m</div>
						<div class="secondary-line">4d needed</div>
					</td>
					<td>
						<div class="primary-line">2d 12h</div>
						<div class="secondary-line">Today, 23:45</div>
					</td>
				</tr>
				<tr class="progress-bar">
					<td colspan="9">
						<progress max="100" value="80"></progress>
					</td>
				</tr>
				</tbody>
			</table>
		</div>

		<div class="app-details">Details</div>

		<div class="app-footer">Footer</div>
	</div>
</template>

<script>
  export default {
    name: 'hadron'
  };
</script>

<style lang="scss">
	@import "assets/styles/styles";

</style>
