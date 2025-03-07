# Dump of HTTP 200 responses for FM map URLs
The files contained in this directory is the raw output from HTML web scrape (one GET HTTP request per http://fortunatemaps.herokuapp.com/map/<#####>) of TagPro map host fortunatemaps.herokuapp.com. By the time this web scrape ended (2025-03-03 12 PM), the latest listed map ID was 88850. Scroll to the bottom for an example item (1 of the 88850 responses) contained within the txt file.
<br><br>
https://fortunatemaps.herokuapp.com/map/1
<br>
...<br>
https://fortunatemaps.herokuapp.com/map/88850
<br><br>
### Example item (HTTP 200 response from GET HTTP request for https://fortunatemaps.herokuapp.com/map/21055):
```
HTTP/1.1 200 OK
Server: Cowboy
Report-To: {"group":"heroku-nel","max_age":3600,"endpoints":[{"url":"https://nel.heroku.com/reports?ts=1739845519&sid=929419e7-33ea-4e2f-85f0-7d8b7cd5cbd6&s=bPXGX8Hd0tfs4EaHyEjg9BWDN%2FUVVqiDForr9zvdDwM%3D"}]}
Reporting-Endpoints: heroku-nel=https://nel.heroku.com/reports?ts=1739845519&sid=929419e7-33ea-4e2f-85f0-7d8b7cd5cbd6&s=bPXGX8Hd0tfs4EaHyEjg9BWDN%2FUVVqiDForr9zvdDwM%3D
Nel: {"report_to":"heroku-nel","max_age":3600,"success_fraction":0.005,"failure_fraction":0.05,"response_headers":["Via"]}
Connection: close
X-Powered-By: Express
Ratelimit-Limit: 200
Ratelimit-Remaining: 194
Ratelimit-Reset: 6
Content-Type: text/html; charset=utf-8
Content-Length: 29070
Etag: W/"718e-SGoqqgr4F1nW1a6V4pn2JxBnDz4"
Date: Tue, 18 Feb 2025 02:25:20 GMT
Via: 1.1 vegur

<!doctype html>
<html lang="en">
	<head>
		<!-- Required meta tags -->
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<meta http-equiv="Content-Type" content="text/html; charset=utf-8" />

<link rel="icon" 
	type="image/png" 
	href="/assets/favicon.png">

<!-- Twitter Card data -->

<!-- Open Graph data -->
<meta property="og:type" content="article" />
<meta property="og:url" content="https://fortunatemaps.herokuapp.com" />
<meta property="og:site_name" content="FortunateMaps" />


<meta name="twitter:title" content="Mars Climb">
<meta name="twitter:image" content="/preview/21055.jpeg">
<meta property="og:image" content="/preview/21055.jpeg" />
<meta name="description" content="by Ball-E" />
<meta name="twitter:card" content="by Ball-E">
<meta name="twitter:description" content="by Ball-E">
<meta property="og:description" content="by Ball-E" />


<!-- Bootstrap CSS -->
<link rel="stylesheet" href="/vendor/bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="/vendor/flatly.min.css">
<link rel="stylesheet" type="text/css" href="/css/global.css">
<link rel="stylesheet" type="text/css" href="/css/badges.css">
<script src="https://kit.fontawesome.com/9668e52905.js" crossorigin="anonymous"></script>
<!-- <script>
	if(location.hostname === 'fortunatemaps.herokuapp.com') {
		location.hostname = 'fortunatemaps.subaverage.site';
	}
</script> -->
		
		<link rel="stylesheet" href="https://cdn.jsdelivr.net/simplemde/latest/simplemde.min.css">
		<link rel="stylesheet" type="text/css" href="/css/map.css">

		<title>Mars Climb by Ball-E</title>
	</head>
	<body>
		<nav class="navbar navbar-expand-md navbar-dark bg-primary fixed-top">
	<a class="navbar-brand" href="/">
		<img src="/assets/logo.png" width="32" height="32" alt="" loading="lazy">
	</a>
	<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarsExampleDefault" aria-controls="navbarsExampleDefault" aria-expanded="false" aria-label="Toggle navigation">
		<span class="navbar-toggler-icon"></span>
	</button>

	<div class="collapse navbar-collapse" id="navbarsExampleDefault">
		<ul class="navbar-nav">
			<li class="nav-item">
				<a class="nav-link in-site" href="/">Home</a>
			</li>
			<li class="nav-item">
				<a class="nav-link in-site" href="/editor">Editor</a>
			</li>
			<li class="nav-item" style='display:none'>
				<a class="nav-link in-site" href="/profile/">Profile</a>
			</li>
			<!-- <li class="nav-item">
				<a class="nav-link" href="https://tagpro.koalabeast.com/maps" target="_blank">Rotation</a>
			</li> -->
			<li class="nav-item ml-auto">
				<a class="nav-link" href="https://discord.gg/JBy3BtN" target="_blank">Mapmaking Discord</a>
			</li>
			<li class="nav-item">
				<a class="nav-link" href="https://github.com/raikutro/fortunatemaps" target="_blank">GitHub</a>
			</li>
		</ul>
		<form class="form-inline my-2 my-lg-0" action="javascript:void(0)" id="searchForm">
			<div class="input-group">
				<input class="form-control" type="text" id="searchText" placeholder="Search" aria-label="Search">
				<div class="input-group-append">
					<button class="btn btn-secondary" type="submit">Search</button>
				</div>
			</div>
		</form>
		<div class="account-buttons">
			<a class="sign-in-link" href="/sign_in">
						<div class="sign-in-button">
							<img src="/assets/logos/ctfauth.png"/> <span>Sign in with CTFAuth</span>
						</div>
					</a>
		</div>
	</div>
</nav>

<script>
	const navLink = document.querySelector(`.nav-link.in-site[href*="${location.pathname.split("/")[1] || "/"}"]`);
	if(navLink) navLink.parentElement.classList.add("active");
</script>

		<main role="main" class="container">
			<div class="row mb-2">
				<div class="col-md-8">
					<div class="card">
						<img
							src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAADTCAMAAABQkwh3AAAAMFBMVEUAAAC5AAAZAJSAgADKwAB4eHhAgFDU1NRAUID/gACAcECAQHAAdQD//wAgICA3NzemEqUwAAAO4UlEQVR4AQHWDinxAAAAAAABAgEDBAMCAQIAAAAAAAAAAAAFBQUFBQUFBQUAAAAAAAAAAAAABQUEBAQFBQAAAAAAAAAAAAAABQYHBwcIBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQkHBwcJBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQkHBwcJBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQkHBwcJBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQkHBwcJBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAFBQcHBwcHBQUAAAAAAAAAAAAFBAcHBwcHBAUAAAAAAAAAAAAFCgcHBwcHCwUAAAAAAAAAAAUFBQcHBwcHBQUFAAAAAAAAAAUDDAcHCQcHDAMFAAAAAAAAAAUDDAcHBwcHDAMFAAAAAAAAAAUDDAcHBwcHDAMFAAAAAAAAAAUFBQoHBwcLBQUFAAAAAAAAAAAAAAUMDAwFAAAAAAAAAAAAAAAABQUHBwcFBQAAAAAAAAAAAAAABQQHBwcEBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQoHBwcLBQAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAFBQUHCQcFBQUAAAAAAAAAAAAFBAcHBwcHBAUAAAAAAAAAAAAFCgcHBwcHCwUAAAAAAAAAAAAABQoHBwcLBQAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUMDAwFAAAAAAAAAAAAAAAFBQYNDQ0IBQUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBQoNDQ0LBQUAAAAAAAAAAAAFAAUMDAwFAAUAAAAAAAAAAAAFBQYNDQ0IBQUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBQoNDQ0LBQUAAAAAAAAAAAAFAAUMDAwFAAUAAAAAAAAAAAAFBQYNDQ0IBQUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBQoNDQ0LBQUAAAAAAAAAAAAFAAUMDAwFAAUAAAAAAAAAAAAFBQYNDQ0IBQUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBQoNDQ0LBQUAAAAAAAAAAAAFBQUMDAwFBQUAAAAAAAAAAAUFBQUHBwcFBQUFAAAAAAAAAAUEBwcHBwcHBwQFAAAAAAAAAAUEBwcHBwcHBwQFAAAAAAAAAAUFBQUHBwcIBQUFAAAAAAAAAAAAAAUHBwcHCAUAAAAAAAAAAAAAAAUKBwcHBwUAAAAAAAAAAAAAAAUFCgcHBwUAAAAAAAAAAAAAAAUFBQcHBwUAAAAAAAAAAAAAAAUOBwcHBwUAAAAAAAAAAAAAAAUHBwcHBwUAAAAAAAAAAAAAAAUHBwcHCwUAAAAAAAAAAAAAAAUHBwcLBQUAAAAAAAAAAAAAAAUHBwcFBQUAAAAAAAAAAAAAAAUHBwcHDgUAAAAAAAAAAAAAAAUHBwcHBwUAAAAAAAAAAAAAAAUKBwcHBwUAAAAAAAAAAAAAAAUFCgcHBwUAAAAAAAAAAAAAAAUFBQcHBwUAAAAAAAAAAAAAAAUHBwcHBwUAAAAAAAAAAAAAAAUHBwcHCwUAAAAAAAAAAAAABQYHBwcLBQAAAAAAAAAAAAAFBgcHBwsFAAAAAAAAAAAAAAUGBwcHCwUAAAAAAAAAAAAABQYHBwcLBQAAAAAAAAAAAAAFBg0HBwsFAAAAAAAAAAAAAAUGBwcNCwUAAAAAAAAAAAAAAAUHBwcHBAUAAAAAAAAAAAAAAAUHBwcHBAUAAAAAAAAAAAAAAAUHBwcLBQUAAAAAAAAAAAAAAAUHBwsFAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAFBQUAAAAAAAAAAAUHBwUFBQUGBAgFAAAAAAAAAAUHBwUGBwcHBwcFAAAAAAAAAAUHBwUHBwcHBwsFAAAAAAAAAAUHBwUHBQUFBQUFBQUFBQUFAAUHBwcHBwcHBwcHBwcHBwQFAAUHBwcHBwcHBwcHBwcHBwQFAAUHBwUFDw8PDw8PDw8PDw8FAAUMDAUFBQUFBQUFBQUFBQUFAAUDAwUAAAUFBQUFAAAAAAAAAAUFBQUAAAUGBAgFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcIAAAAAAAAAAAAAAAAAAUHBwcLAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAYHBwcFAAAAAAAAAAAAAAAAAAoHBwcFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcIBQAAAAAAAAAAAAAAAAUKBwcHCAUFAAAAAAAAAAAAAAAFCgcHBwcFAAAAAAAAAAAAAAAABQoHBwcIBQAAAAAAAAAAAAAAAAUKBwcHCAUFAAAAAAAAAAAAAAAFCgcHBw8FAAAAAAAAAAAAAAAABQcHBw8FAAAAAAAAAAAAAAAFBgcHBw8FAAAAAAAAAAAAAAUGBwcHCwUFAAAAAAAAAAAABQYHBwcLBQAAAAAAAAAABQUFBgcHBwsFAAAAAAAAAAAABQcHBwcHCwUAAAAAAAAAAAAABQcHBwcLBQAAAAAAAAAAAAAFBgcHBwsFAAAAAAAAAAAAAAUGBwcHCwUFAAAAAAAAAAAABQYHBwcLBQUFAAAAAAAAAAAFBQcHBwsFBQUFAAAAAAAAAAAFDAcHBwUEBAQFAAAAAAAAAAAFDAcHBwUHBwcFAAAAAAAAAAAFDAcHBwYHBwcFAAAAAAAAAAAFDAcHBwcHBwcFAAAAAAAAAAAFBwcHBwsFBQUFAAAAAAAAAAAFBwcHBwUFBQUFAAAAAAAAAAAFCgcHBwwHCAUFAAAAAAAAAAAABQoHBwwHBwgFAAAAAAAAAAAAAAUKBwwHBwcFAAAAAAAAAAAAAAAFBQUMDAwFAAAAAAAAAAAAAAAAAAUEBAQFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAUHBwcFBQUAAAAAAAAAAAAABQUHBwcHBwgFAAAAAAAAAAAFBgcHBwcHBwcIBQAAAAAAAAAFBwcHBwcHBwcHDwUAAAAAAAUGBwcHBwsFCgcHBwgFAAAABQYHBwcHCwYABQ8HBwcFAAAFBgcHBwcLBgAACAUKBwcFAAUFBwcHBwwFAAAACwUGBwcFAAUPBwcHCwUGAAAABQ8HBwcFAAUPBwcHBQAAAAALBgcHBwsFAAUPBwcHCAoABQUGBwcHDwUAAAUFBwcHBwgFBQ8HBwcLBQUAAAAFCgcHBwcHBwcHBwsFAAAAAAAABQoHBwcHBwcHDwUAAAAAAAAAAAUKBwcHBwcHCAUFAAAAAAAAAAUGBwcHBwcHBwgFAAAAAAAAAAUEBwcHBwcHBwQFAAAAAAAAAAUKBwcHBwcHBwsFAAAAAAAAAAAFCgcHBwcHCwUAAAAAAAAAAAAABQoHBwcLBQAAAAAAAAAAAAAAAAUMDAwFAAAAAAAAAAAAAAAAAAUDAwMFAAAAAAAAAAAABQUFBQUFBQUFBQUFBQAAAAAFBQQEBAUAAAAFBAQEBQUAAAUFBwcHBwUFBQUFBwcHBwUFAAUHBwcHBwcHBwcHBwcHBwcFAAUHBwcHBwcHBwcHBwcHBwcFAAUFBwcHBwcHBwcHBwcHBwUFAAAFBQcHBwcHBwcHBwcHBQUAAAAABQUFBQUFBQUFBQUFBQAAIakuDDtkxuIAAAAASUVORK5CYII="
							data-lazyrendermode="pixelated"
							data-src="/preview/21055.jpeg"
							class="card-img-top"
							alt="Mars Climb by Ball-E"
						/>
						<div class="card-body">
							<div class="text-center">
								<h5 class="card-title">
									<b>Mars Climb</b> by <b>Ball-E</b>
								</h5>
								<!-- <p class="card-text">Look at this map.</p> -->
							</div>
							<hr>
							<div class="btn-group w-100" role="group" aria-label="Map Controls">
								<a type="button" class="btn btn-primary" href="/test/21055">Test</a>
								<a type="button" class="btn btn-primary" href="/preview/21055">Fullsize Preview</a>
								<a type="button" class="btn btn-primary" href="/png/21055">.PNG</a>
								<a type="button" class="btn btn-primary" href="/json/21055">.JSON</a>
								<a type="button" class="btn btn-primary" href="/editor?mapid=21055">Remix this map</a>
							</div>
						</div>
					</div>
				</div>
				<div class="col-md-4">
					<div class="card stats-card">
						<div class="card-body">
							<div class="dropdown w-100">
								<button class="btn btn-primary w-100 dropdown-toggle" type="button" id="dropdownVersionsButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
									Versions
								</button>
								<div class="dropdown-menu" aria-labelledby="dropdownVersionsButton">
									
											<a class="dropdown-item" href="/map/21055">
												Mars Climb by Ball-E (21055)
											</a>
										
								</div>
							</div>
							<div class="dropdown w-100 mt-2">
								<button class="btn btn-primary w-100 dropdown-toggle" type="button" id="dropdownRemixesButton" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
									Remixes
								</button>
								<div class="dropdown-menu" aria-labelledby="dropdownRemixesButton">
									
								</div>
							</div>
							<hr>
							
							<div class="map-data">
								<table class="data-table">
									<tbody>
										<tr>
											<td>Upload Date</td>
											<td data-map-property="date">
												2/29/2016, 8:07:59 AM
											</td>
										</tr>
										<tr>
											<td>Authors</td>
											<td>
												Anonymous
											</td>
										</tr>
										<tr>
											<td>Tags</td>
											<td>
												<span
															class="tag badge badge-primary"
															style="background: #003F00; color: #eee"
														>U-M Transfer</span>
											</td>
										</tr>
									</tbody>
								</table>
							</div>
							<hr>
							<pre class="map-description">-- Original U-M ID: 24428 --
No description</pre>
						</div>
					</div>
				</div>
			</div>
			<hr>
			<div class="comment-editor-container mb-2">
				<div class="markdown-container">
					<textarea id="commentInput"></textarea>
				</div>
				<button class="btn btn-primary w-100" id="submitCommentBtn">Submit</button>
				<hr>
			</div>
			<div class="card mb-2">
				<div class="card-header">
					Comments
				</div>
				<div class="card-body" id="commentsContainer">
					
				</div>
			</div>
		</main>

		<div class="modal fade" id="mapSettingsModal" tabindex="-1" aria-labelledby="mapSettingsModalLabel" aria-hidden="true">
			<div class="modal-dialog">
				<div class="modal-content">
					<div class="modal-header">
						<h5 class="modal-title" id="mapSettingsModalLabel">Map Settings</h5>
						<button type="button" class="close" data-dismiss="modal" aria-label="Close">
							<span aria-hidden="true">&times;</span>
						</button>
					</div>
					<div class="modal-body">
						<b>Map Name and Author:</b>
						<div class="input-group mt-2">
							<input type="text" class="form-control" id="mapNameInput" value="Mars Climb" maxlength="150" placeholder="Map Name">
							<input type="text" class="form-control" id="mapAuthorInput" value="Ball-E" maxlength="150" placeholder="Map Author">
						</div>
						<hr>

						<b class="tag-container">Authors: <span id="authorsDisplay"></span></b>
						<div class="input-group mt-2" id="authorsGroup">
							<input type="text" class="form-control" id="authorsInput" placeholder="Author ID or Username" maxlength="24" autocomplete="no">
							<div class="input-group-append">
								<button type="button" class="btn btn-secondary" id="addAuthorBtn">Add</button>
							</div>
						</div>
						<ul id="authorSearchList"></ul>

						<p></p>

						<b class="tag-container">Tags: <span id="tagsDisplay">
							
						</span></b>
						<div class="input-group mt-2" id="tagsGroup">
							<input type="text" class="form-control" id="tagsInput" placeholder="Tag Name" maxlength="16">
							<div class="input-group-append">
								<button type="button" class="btn btn-secondary" id="addTagBtn">Add</button>
								<button type="button" class="btn btn-secondary dropdown-toggle dropdown-toggle-split" data-toggle="dropdown">
									<span class="sr-only">Toggle Dropdown</span>
								</button>
								<div class="dropdown-menu">
									<a class="dropdown-item" href="javascript:void(0)" data-type="CTF">CTF</a><a class="dropdown-item" href="javascript:void(0)" data-type="NF">NF</a><a class="dropdown-item" href="javascript:void(0)" data-type="DTF">DTF</a><a class="dropdown-item" href="javascript:void(0)" data-type="2NF">2NF</a><a class="dropdown-item" href="javascript:void(0)" data-type="MARS BALL">Mars Ball</a><a class="dropdown-item" href="javascript:void(0)" data-type="MINIGAME">Minigame</a>
								</div>
							</div>
						</div>
						<hr/>
						<b>Description:</b>
						<textarea class="form-control" id="descriptionText"></textarea>
						<hr>
						<div class="input-group w-100">
							<div class="input-group-prepend">
								<span class="input-group-text">Unlisted</span>
							</div>
							<div class="input-group-append">
								<div class="input-group-text">
									<input type="checkbox" id="unlistedCheck" >
								</div>
							</div>
						</div>
					</div>
					<div class="modal-footer">
						<button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
						<button type="button" class="btn btn-primary" id="saveMapSettings">Save changes</button>
					</div>
				</div>
			</div>
		</div>

		<footer class="py-3 bg-primary text-light">
			<div class="container">
				<p class="text-center m-0">Developed by Electro ⚡</p>
			</div>
		</footer>

		<script type="text/javascript">window.MAP_DATA = {"_id":"62219c3ce8aa36d45ca6feeb","name":"Mars Climb","authorIDs":[],"authorName":"Ball-E","description":"-- Original U-M ID: 24428 --\nNo description","dateUploaded":"2016-02-29T08:07:59.125Z","comments":[],"likes":[],"tags":["UMDUMP"],"hiddenTags":[],"mapID":21055,"json":"{\"info\":{\"gameMode\":\"gravityCTF\",\"name\":\"Mars Climb\",\"author\":\"Ball-E\"},\"portals\":{\"4,73\":{\"cooldown\":0,\"destination\":{\"y\":68,\"x\":11}},\"4,74\":{\"cooldown\":0,\"destination\":{\"y\":69,\"x\":11}},\"7,161\":{\"cooldown\":0,\"destination\":{\"y\":151,\"x\":7}},\"3,204\":{\"cooldown\":0,\"destination\":{\"y\":197,\"x\":12}},\"7,151\":{},\"11,64\":{\"cooldown\":0,\"destination\":{\"y\":59,\"x\":5}},\"15,116\":{\"cooldown\":0,\"destination\":{\"y\":98,\"x\":5}},\"11,54\":{\"cooldown\":0,\"destination\":{\"y\":47,\"x\":11}},\"5,204\":{\"cooldown\":0,\"destination\":{\"y\":197,\"x\":12}},\"9,2\":{\"cooldown\":0,\"destination\":{\"y\":0,\"x\":8}},\"11,33\":{},\"7,2\":{\"cooldown\":0,\"destination\":{\"y\":0,\"x\":8}},\"11,204\":{\"cooldown\":0,\"destination\":{\"y\":197,\"x\":4}},\"5,53\":{\"cooldown\":0,\"destination\":{\"y\":47,\"x\":5}},\"5,54\":{\"cooldown\":0,\"destination\":{\"y\":47,\"x\":5}},\"12,197\":{},\"8,161\":{\"cooldown\":0,\"destination\":{\"y\":151,\"x\":8}},\"5,58\":{\"cooldown\":0,\"destination\":{\"y\":53,\"x\":11}},\"5,59\":{\"cooldown\":0,\"destination\":{\"y\":54,\"x\":11}},\"9,161\":{\"cooldown\":0,\"destination\":{\"y\":151,\"x\":9}},\"8,121\":{\"cooldown\":0,\"destination\":{\"y\":112,\"x\":8}},\"8,2\":{\"cooldown\":0,\"destination\":{\"y\":0,\"x\":8}},\"8,0\":{},\"11,69\":{\"cooldown\":0,\"destination\":{\"y\":64,\"x\":5}},\"11,68\":{\"cooldown\":0,\"destination\":{\"y\":63,\"x\":5}},\"10,42\":{\"cooldown\":0,\"destination\":{\"y\":33,\"x\":11}},\"15,117\":{\"cooldown\":0,\"destination\":{\"y\":99,\"x\":5}},\"5,33\":{},\"11,47\":{},\"11,63\":{\"cooldown\":0,\"destination\":{\"y\":58,\"x\":5}},\"4,204\":{\"cooldown\":0,\"destination\":{\"y\":197,\"x\":12}},\"5,98\":{},\"5,99\":{},\"13,204\":{\"cooldown\":0,\"destination\":{\"y\":197,\"x\":4}},\"8,112\":{},\"11,58\":{\"cooldown\":0,\"destination\":{\"y\":53,\"x\":5}},\"6,42\":{\"cooldown\":0,\"destination\":{\"y\":33,\"x\":5}},\"11,59\":{\"cooldown\":0,\"destination\":{\"y\":54,\"x\":5}},\"5,69\":{\"cooldown\":0,\"destination\":{\"y\":64,\"x\":11}},\"5,68\":{\"cooldown\":0,\"destination\":{\"y\":63,\"x\":11}},\"8,151\":{},\"5,47\":{},\"12,204\":{\"cooldown\":0,\"destination\":{\"y\":197,\"x\":4}},\"11,53\":{\"cooldown\":0,\"destination\":{\"y\":47,\"x\":11}},\"12,73\":{\"cooldown\":0,\"destination\":{\"y\":68,\"x\":5}},\"5,63\":{\"cooldown\":0,\"destination\":{\"y\":58,\"x\":11}},\"12,74\":{\"cooldown\":0,\"destination\":{\"y\":69,\"x\":5}},\"4,197\":{},\"5,64\":{\"cooldown\":0,\"destination\":{\"y\":59,\"x\":11}},\"9,151\":{}},\"fields\":{\"6,188\":{\"defaultState\":\"on\"},\"9,40\":{\"defaultState\":\"on\"},\"9,61\":{\"defaultState\":\"on\"},\"8,61\":{\"defaultState\":\"on\"},\"8,40\":{\"defaultState\":\"on\"},\"9,66\":{\"defaultState\":\"on\"},\"8,66\":{\"defaultState\":\"on\"},\"8,201\":{\"defaultState\":\"on\"},\"7,71\":{\"defaultState\":\"on\"},\"8,51\":{\"defaultState\":\"on\"},\"8,160\":{\"defaultState\":\"on\"},\"7,56\":{\"defaultState\":\"on\"},\"11,36\":{\"defaultState\":\"on\"},\"9,160\":{\"defaultState\":\"on\"},\"7,51\":{\"defaultState\":\"on\"},\"5,38\":{\"defaultState\":\"on\"},\"1,119\":{\"defaultState\":\"on\"},\"8,71\":{\"defaultState\":\"on\"},\"2,154\":{\"defaultState\":\"on\"},\"2,119\":{\"defaultState\":\"on\"},\"2,151\":{\"defaultState\":\"on\"},\"5,37\":{\"defaultState\":\"on\"},\"2,153\":{\"defaultState\":\"on\"},\"2,152\":{\"defaultState\":\"on\"},\"6,159\":{\"defaultState\":\"on\"},\"6,158\":{\"defaultState\":\"on\"},\"9,56\":{\"defaultState\":\"on\"},\"9,71\":{\"defaultState\":\"on\"},\"7,201\":{\"defaultState\":\"on\"},\"8,56\":{\"defaultState\":\"on\"},\"6,157\":{\"defaultState\":\"on\"},\"11,37\":{\"defaultState\":\"on\"},\"7,160\":{\"defaultState\":\"on\"},\"7,61\":{\"defaultState\":\"on\"},\"5,36\":{\"defaultState\":\"on\"},\"7,66\":{\"defaultState\":\"on\"},\"7,40\":{\"defaultState\":\"on\"},\"11,38\":{\"defaultState\":\"on\"},\"9,201\":{\"defaultState\":\"on\"},\"9,51\":{\"defaultState\":\"on\"}},\"switches\":{},\"marsballs\":[{\"y\":4,\"x\":8},{\"y\":122,\"x\":8}],\"spawnPoints\":{\"blue\":[{\"y\":209,\"x\":10,\"radius\":5,\"weight\":1}],\"red\":[{\"y\":209,\"x\":6,\"radius\":5,\"weight\":1}]}}","png":"iVBORw0KGgoAAAANSUhEUgAAABEAAADTCAMAAABQkwh3AAAAMFBMVEUAAAC5AAAZAJSAgADKwAB4eHhAgFDU1NRAUID/gACAcECAQHAAdQD//wAgICA3NzemEqUwAAAO4UlEQVR4AQHWDinxAAAAAAABAgEDBAMCAQIAAAAAAAAAAAAFBQUFBQUFBQUAAAAAAAAAAAAABQUEBAQFBQAAAAAAAAAAAAAABQYHBwcIBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQkHBwcJBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQkHBwcJBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQkHBwcJBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQkHBwcJBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAFBQcHBwcHBQUAAAAAAAAAAAAFBAcHBwcHBAUAAAAAAAAAAAAFCgcHBwcHCwUAAAAAAAAAAAUFBQcHBwcHBQUFAAAAAAAAAAUDDAcHCQcHDAMFAAAAAAAAAAUDDAcHBwcHDAMFAAAAAAAAAAUDDAcHBwcHDAMFAAAAAAAAAAUFBQoHBwcLBQUFAAAAAAAAAAAAAAUMDAwFAAAAAAAAAAAAAAAABQUHBwcFBQAAAAAAAAAAAAAABQQHBwcEBQAAAAAAAAAAAAAABQcHBwcHBQAAAAAAAAAAAAAABQoHBwcLBQAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAFBQUHCQcFBQUAAAAAAAAAAAAFBAcHBwcHBAUAAAAAAAAAAAAFCgcHBwcHCwUAAAAAAAAAAAAABQoHBwcLBQAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUMDAwFAAAAAAAAAAAAAAAFBQYNDQ0IBQUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBQoNDQ0LBQUAAAAAAAAAAAAFAAUMDAwFAAUAAAAAAAAAAAAFBQYNDQ0IBQUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBQoNDQ0LBQUAAAAAAAAAAAAFAAUMDAwFAAUAAAAAAAAAAAAFBQYNDQ0IBQUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBQoNDQ0LBQUAAAAAAAAAAAAFAAUMDAwFAAUAAAAAAAAAAAAFBQYNDQ0IBQUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBA0NDQ0NBAUAAAAAAAAAAAAFBQoNDQ0LBQUAAAAAAAAAAAAFBQUMDAwFBQUAAAAAAAAAAAUFBQUHBwcFBQUFAAAAAAAAAAUEBwcHBwcHBwQFAAAAAAAAAAUEBwcHBwcHBwQFAAAAAAAAAAUFBQUHBwcIBQUFAAAAAAAAAAAAAAUHBwcHCAUAAAAAAAAAAAAAAAUKBwcHBwUAAAAAAAAAAAAAAAUFCgcHBwUAAAAAAAAAAAAAAAUFBQcHBwUAAAAAAAAAAAAAAAUOBwcHBwUAAAAAAAAAAAAAAAUHBwcHBwUAAAAAAAAAAAAAAAUHBwcHCwUAAAAAAAAAAAAAAAUHBwcLBQUAAAAAAAAAAAAAAAUHBwcFBQUAAAAAAAAAAAAAAAUHBwcHDgUAAAAAAAAAAAAAAAUHBwcHBwUAAAAAAAAAAAAAAAUKBwcHBwUAAAAAAAAAAAAAAAUFCgcHBwUAAAAAAAAAAAAAAAUFBQcHBwUAAAAAAAAAAAAAAAUHBwcHBwUAAAAAAAAAAAAAAAUHBwcHCwUAAAAAAAAAAAAABQYHBwcLBQAAAAAAAAAAAAAFBgcHBwsFAAAAAAAAAAAAAAUGBwcHCwUAAAAAAAAAAAAABQYHBwcLBQAAAAAAAAAAAAAFBg0HBwsFAAAAAAAAAAAAAAUGBwcNCwUAAAAAAAAAAAAAAAUHBwcHBAUAAAAAAAAAAAAAAAUHBwcHBAUAAAAAAAAAAAAAAAUHBwcLBQUAAAAAAAAAAAAAAAUHBwsFAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAAAAAAAAAAAAAAAAUHBwUAAAAFBQUAAAAAAAAAAAUHBwUFBQUGBAgFAAAAAAAAAAUHBwUGBwcHBwcFAAAAAAAAAAUHBwUHBwcHBwsFAAAAAAAAAAUHBwUHBQUFBQUFBQUFBQUFAAUHBwcHBwcHBwcHBwcHBwQFAAUHBwcHBwcHBwcHBwcHBwQFAAUHBwUFDw8PDw8PDw8PDw8FAAUMDAUFBQUFBQUFBQUFBQUFAAUDAwUAAAUFBQUFAAAAAAAAAAUFBQUAAAUGBAgFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcIAAAAAAAAAAAAAAAAAAUHBwcLAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAYHBwcFAAAAAAAAAAAAAAAAAAoHBwcFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAUHBwcIBQAAAAAAAAAAAAAAAAUKBwcHCAUFAAAAAAAAAAAAAAAFCgcHBwcFAAAAAAAAAAAAAAAABQoHBwcIBQAAAAAAAAAAAAAAAAUKBwcHCAUFAAAAAAAAAAAAAAAFCgcHBw8FAAAAAAAAAAAAAAAABQcHBw8FAAAAAAAAAAAAAAAFBgcHBw8FAAAAAAAAAAAAAAUGBwcHCwUFAAAAAAAAAAAABQYHBwcLBQAAAAAAAAAABQUFBgcHBwsFAAAAAAAAAAAABQcHBwcHCwUAAAAAAAAAAAAABQcHBwcLBQAAAAAAAAAAAAAFBgcHBwsFAAAAAAAAAAAAAAUGBwcHCwUFAAAAAAAAAAAABQYHBwcLBQUFAAAAAAAAAAAFBQcHBwsFBQUFAAAAAAAAAAAFDAcHBwUEBAQFAAAAAAAAAAAFDAcHBwUHBwcFAAAAAAAAAAAFDAcHBwYHBwcFAAAAAAAAAAAFDAcHBwcHBwcFAAAAAAAAAAAFBwcHBwsFBQUFAAAAAAAAAAAFBwcHBwUFBQUFAAAAAAAAAAAFCgcHBwwHCAUFAAAAAAAAAAAABQoHBwwHBwgFAAAAAAAAAAAAAAUKBwwHBwcFAAAAAAAAAAAAAAAFBQUMDAwFAAAAAAAAAAAAAAAAAAUEBAQFAAAAAAAAAAAAAAAAAAUHBwcFAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAYHBwcIAAAAAAAAAAAAAAAAAAoHBwcLAAAAAAAAAAAAAAAAAAUHBwcFBQUAAAAAAAAAAAAABQUHBwcHBwgFAAAAAAAAAAAFBgcHBwcHBwcIBQAAAAAAAAAFBwcHBwcHBwcHDwUAAAAAAAUGBwcHBwsFCgcHBwgFAAAABQYHBwcHCwYABQ8HBwcFAAAFBgcHBwcLBgAACAUKBwcFAAUFBwcHBwwFAAAACwUGBwcFAAUPBwcHCwUGAAAABQ8HBwcFAAUPBwcHBQAAAAALBgcHBwsFAAUPBwcHCAoABQUGBwcHDwUAAAUFBwcHBwgFBQ8HBwcLBQUAAAAFCgcHBwcHBwcHBwsFAAAAAAAABQoHBwcHBwcHDwUAAAAAAAAAAAUKBwcHBwcHCAUFAAAAAAAAAAUGBwcHBwcHBwgFAAAAAAAAAAUEBwcHBwcHBwQFAAAAAAAAAAUKBwcHBwcHBwsFAAAAAAAAAAAFCgcHBwcHCwUAAAAAAAAAAAAABQoHBwcLBQAAAAAAAAAAAAAAAAUMDAwFAAAAAAAAAAAAAAAAAAUDAwMFAAAAAAAAAAAABQUFBQUFBQUFBQUFBQAAAAAFBQQEBAUAAAAFBAQEBQUAAAUFBwcHBwUFBQUFBwcHBwUFAAUHBwcHBwcHBwcHBwcHBwcFAAUHBwcHBwcHBwcHBwcHBwcFAAUFBwcHBwcHBwcHBwcHBwUFAAAFBQcHBwcHBwcHBwcHBQUAAAAABQUFBQUFBQUFBQUFBQAAIakuDDtkxuIAAAAASUVORK5CYII=","versionSource":21055,"isRemix":false,"unlisted":false,"__v":0}</script>

		<!-- Optional JavaScript -->
<script type="text/javascript" src="/vendor/jquery.min.js"></script>
<script type="text/javascript" src="/vendor/popper.min.js"></script>
<script type="text/javascript" src="/vendor/bootstrap.min.js"></script>
<script type="text/javascript" src="/vendor/purify.min.js"></script>
<script type="text/javascript" src="https://unpkg.com/marked@4.0.12/marked.min.js"></script>
<script type="text/javascript">window.SETTINGS = {"CTF_AUTH_URL":"https://ctfauth.herokuapp.com/api/v2","DEV_MODE":false,"MAPS":{"PREVIEW_QUALITY":0.7,"THUMBNAIL_QUALITY":0.9,"THUMBNAIL_SIZE":400,"MAX_PNG_LENGTH":1048576,"MAX_JSON_LENGTH":1048576},"SITE":{"MAPS_PER_PAGE":24,"LOGIN_EXPIRATION_TIME_LIMIT":8640000000,"COOKIE_TOKEN_NAME":"nekotizer","MAP_NAME_LENGTH":150,"AUTHOR_LENGTH":150,"TAG_NAME_MAX_LENGTH":16,"MAX_TAGS":10,"MAX_AUTHORS":24,"CERTIFICATIONS":{"0":{"priority":10,"name":"Nothing","backgroundColor":"gray","textColor":"#EEEEEE"},"1":{"priority":10,"name":"F-M Developer","backgroundColor":"#69BF4A","textColor":"#EEEEEE"},"2":{"priority":9,"name":"MTC","backgroundColor":"#4CAF50","textColor":"#EEEEEE"},"3":{"priority":8,"name":"TPFG","backgroundColor":"#5DB4E8","textColor":"#EEEEEE"}},"ADMIN_ONLY_TAGS":["ROTATION","RETIRED","UMDUMP"],"TAGS":{"CTF":{"name":"CTF","backgroundColor":"linear-gradient(45deg, #DF5349 50%, #4971DF 50%)","textColor":"#EEEEEE"},"NF":{"name":"NF","backgroundColor":"#FFEB3B","textColor":"#111111"},"DTF":{"name":"DTF","backgroundColor":"#673AB7","textColor":"#EEEEEE"},"2NF":{"name":"2NF","backgroundColor":"linear-gradient(45deg, #FF9800 33%, #F0F0F0 33% 66%, #FF9800 33%)","textColor":"#111111"},"MARS BALL":{"name":"Mars Ball","backgroundColor":"maroon","textColor":"#EEEEEE"},"MINIGAME":{"name":"Minigame","backgroundColor":"#B73AB3","textColor":"#EEEEEE"},"ROTATION":{"name":"Rotation","backgroundColor":"linear-gradient(90deg, #33C738, #A4D270)","textColor":"#EEEEEE"},"RETIRED":{"name":"Retired","backgroundColor":"linear-gradient(90deg, #C4C4C4, #D1D1D1)","textColor":"#111111"},"UMDUMP":{"name":"U-M Transfer","backgroundColor":"#003F00","textColor":"#eee"}}},"ERRORS":{"LOGIN_ERROR":{"err":"An error occurred while logging in","code":"LOGIN.LOGIN_ERROR"},"INVALID_LOGIN_TOKEN":{"err":"Your login token has expired","code":"LOGIN.INVALID_TOKEN"},"ALREADY_REGISTERED":{"err":"This profile has already been registered","code":"REGISTER.ALREADY_REGISTERED"},"INVALID_MAP_ID":{"err":"That map ID is invalid","code":"SEARCH.INVALID_MAP_ID"},"NOT_FOUND":{"err":"That resource could not be located","code":"SEARCH.NOT_FOUND"},"MAX_PAGE_LIMIT":{"err":"The page you were trying to access is out of range. Please use a smaller value","code":"SEARCH.MAX_PAGE_LIMIT"},"TEST_MAP_LINK_FAIL":{"err":"Sorry, we could not start up a test map","code":"TEST.TEST_MAP_LINK_FAIL"},"UPLOAD_MAX_SIZE":{"err":"A size error occurred while uploading your map.","code":"UPLOAD.MAX_SIZE"},"PREVIEW_GENERATION":{"err":"An error occurred while generating map preview","code":"CREATION.PREVIEW_GENERATION"},"PREVIEW_WRITING":{"err":"An error occurred while saving the map preview","code":"CREATION.PREVIEW_WRITING"},"THUMBNAIL_GENERATION":{"err":"An error occurred while generating map thumbnail","code":"CREATION.THUMBNAIL_GENERATION"}},"FILLERS":{"BIO":["404 Biography Not Found","No Description","Nothing to be said here","I'm too lazy to write a biography."]}};window.PROFILE = null</script>
<script type="text/javascript" src="/js/global.js"></script>
<script type="text/javascript" src="/js/search.js"></script>

		<script src="https://cdn.jsdelivr.net/simplemde/latest/simplemde.min.js"></script>
		<script type="text/javascript" src="/js/tag_input.js"></script>
		<script type="text/javascript" src="/js/map.js"></script>
	</body>
</html>
```
<br>

Map IDs contained in each file
---
**tp fm crawl responses main (count = 88344):**<br>
Cetera

**tp fm crawl responses stragglers (count = 257):**<br>
1444<br>
1563<br>
1896<br>
1897<br>
1898<br>
1899<br>
1900<br>
2651<br>
2652<br>
2653<br>
2654<br>
2655<br>
2656<br>
2657<br>
2658<br>
2659<br>
2660<br>
2661<br>
2662<br>
2663<br>
2664<br>
2665<br>
2666<br>
2667<br>
2668<br>
2669<br>
2670<br>
2671<br>
2672<br>
2673<br>
2674<br>
2675<br>
2676<br>
2677<br>
2678<br>
2679<br>
2680<br>
2681<br>
2682<br>
2683<br>
2684<br>
2685<br>
2686<br>
2687<br>
2688<br>
2689<br>
2690<br>
2691<br>
2692<br>
2693<br>
2694<br>
2695<br>
2696<br>
2697<br>
2698<br>
2699<br>
2700<br>
2701<br>
2702<br>
2703<br>
2704<br>
2705<br>
2706<br>
2707<br>
2708<br>
2709<br>
2710<br>
2711<br>
2712<br>
2713<br>
2714<br>
2715<br>
2716<br>
2717<br>
2718<br>
2719<br>
2720<br>
2721<br>
2722<br>
2723<br>
2724<br>
2725<br>
2726<br>
2727<br>
2728<br>
2729<br>
2730<br>
2731<br>
2732<br>
2733<br>
2734<br>
2735<br>
2736<br>
2737<br>
2738<br>
2739<br>
2740<br>
2741<br>
2742<br>
2743<br>
2744<br>
2745<br>
2746<br>
2747<br>
2748<br>
2749<br>
2750<br>
2751<br>
2752<br>
2753<br>
2754<br>
2755<br>
2756<br>
2757<br>
2758<br>
2759<br>
2760<br>
2761<br>
2762<br>
2763<br>
2764<br>
2765<br>
2766<br>
2767<br>
2768<br>
2769<br>
2770<br>
2771<br>
2772<br>
2773<br>
2774<br>
2775<br>
2776<br>
2777<br>
2778<br>
2779<br>
2780<br>
2781<br>
2782<br>
2783<br>
2784<br>
2785<br>
2786<br>
2787<br>
2788<br>
2789<br>
2790<br>
2791<br>
2792<br>
2793<br>
2794<br>
2795<br>
2796<br>
2797<br>
2798<br>
2799<br>
2800<br>
2801<br>
2802<br>
2803<br>
2804<br>
2805<br>
2806<br>
13331<br>
14323<br>
14324<br>
14325<br>
14326<br>
14327<br>
14328<br>
14329<br>
14330<br>
22702<br>
23334<br>
23335<br>
23336<br>
23337<br>
26807<br>
28818<br>
32346<br>
33014<br>
33015<br>
33016<br>
33017<br>
33018<br>
33019<br>
43559<br>
44109<br>
50907<br>
50908<br>
50909<br>
50910<br>
50911<br>
50912<br>
50913<br>
50914<br>
50915<br>
50916<br>
50917<br>
50918<br>
50919<br>
50920<br>
50921<br>
52448<br>
52449<br>
52450<br>
52451<br>
52452<br>
52453<br>
52454<br>
52455<br>
52456<br>
52457<br>
52458<br>
52459<br>
52460<br>
52461<br>
52462<br>
57575<br>
58018<br>
58669<br>
58670<br>
58671<br>
59097<br>
59098<br>
59099<br>
59100<br>
59101<br>
59102<br>
59103<br>
59104<br>
59105<br>
71974<br>
72629<br>
73510<br>
73511<br>
73512<br>
73513<br>
73514<br>
73515<br>
73516<br>
73517<br>
73518<br>
73519<br>
83186<br>
83669<br>
84322<br>
84323<br>
84324<br>
84325<br>
84326<br>
84327<br>
84328<br>
84329<br>
84330<br>
84331<br>
84332<br>

**Map IDs with non-existent pages on fortunatemaps.herokuapp.com (count = 249):**<br>
2479<br>
2480<br>
2481<br>
3560<br>
3561<br>
3563<br>
3565<br>
4141<br>
4142<br>
4143<br>
7033<br>
14012<br>
14013<br>
15004<br>
15005<br>
16832<br>
18354<br>
20748<br>
22195<br>
22196<br>
22426<br>
25494<br>
25989<br>
26715<br>
26716<br>
26717<br>
28474<br>
28475<br>
28476<br>
30282<br>
30283<br>
30284<br>
30285<br>
30286<br>
30287<br>
30288<br>
30289<br>
30871<br>
31254<br>
32095<br>
32096<br>
32100<br>
32673<br>
32674<br>
32675<br>
32676<br>
32711<br>
33089<br>
33090<br>
33091<br>
34509<br>
34510<br>
34511<br>
34512<br>
34513<br>
34516<br>
34517<br>
34519<br>
34520<br>
34521<br>
34522<br>
34796<br>
36923<br>
36924<br>
37155<br>
37156<br>
37158<br>
37309<br>
37437<br>
37438<br>
37439<br>
37578<br>
39521<br>
39522<br>
39523<br>
39524<br>
41081<br>
41182<br>
42251<br>
42392<br>
42902<br>
42903<br>
42979<br>
45181<br>
45932<br>
45939<br>
45946<br>
46736<br>
46976<br>
46978<br>
46979<br>
47351<br>
47892<br>
48037<br>
48913<br>
50784<br>
50785<br>
50786<br>
50787<br>
50788<br>
50789<br>
50790<br>
50792<br>
51440<br>
51903<br>
51904<br>
51905<br>
53391<br>
53601<br>
53935<br>
53936<br>
54292<br>
54370<br>
54371<br>
54372<br>
54963<br>
54968<br>
55047<br>
55048<br>
55049<br>
55050<br>
55051<br>
55052<br>
55148<br>
55149<br>
55150<br>
55151<br>
55152<br>
55153<br>
55154<br>
55155<br>
55156<br>
55157<br>
55158<br>
55159<br>
55160<br>
55161<br>
55162<br>
55163<br>
55164<br>
55165<br>
55166<br>
55252<br>
55301<br>
55302<br>
55303<br>
55304<br>
55305<br>
55376<br>
55826<br>
55827<br>
55940<br>
55941<br>
55942<br>
55943<br>
55944<br>
56938<br>
56939<br>
56940<br>
56941<br>
56942<br>
57586<br>
57587<br>
57626<br>
57627<br>
58605<br>
58649<br>
58650<br>
58651<br>
58652<br>
59066<br>
59166<br>
59631<br>
59885<br>
60347<br>
60582<br>
60583<br>
60584<br>
60585<br>
60586<br>
61023<br>
61262<br>
61263<br>
61264<br>
61265<br>
61424<br>
61460<br>
61461<br>
61462<br>
61824<br>
62097<br>
62209<br>
62546<br>
62547<br>
62548<br>
62549<br>
62551<br>
62552<br>
62553<br>
62771<br>
62796<br>
62797<br>
62798<br>
62800<br>
62801<br>
63194<br>
63292<br>
63293<br>
63295<br>
63296<br>
65942<br>
66258<br>
66262<br>
67633<br>
69147<br>
69736<br>
69737<br>
69738<br>
69739<br>
70819<br>
70820<br>
70821<br>
71918<br>
71919<br>
71920<br>
71921<br>
71931<br>
71935<br>
72314<br>
72315<br>
72316<br>
72318<br>
72651<br>
72939<br>
72940<br>
72941<br>
73017<br>
73972<br>
73973<br>
73974<br>
73975<br>
73976<br>
73977<br>
73978<br>
73979<br>
73980<br>
73981<br>
73982<br>
74024<br>
<br>
