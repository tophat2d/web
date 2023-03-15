</div>

<div class="px-4 py-5 my-5 text-center">
	<img class="d-block mx-auto mb-4 no-aa" src="/logo.png" alt="" height="128">
	<h1 class="display-5 fw-bold">Tophat Game Framework</h1>
	<div class="col-lg-6 mx-auto">
	  <p class="lead mb-4">A 2D Framework for making games in <a
		href="https://github.com/vtereshkov/umka-lang">Umka</a></p>
	  <div class="d-grid gap-2 d-sm-flex justify-content-sm-center">
		<a href="https://th.mrms.cz/dl/" class="btn btn-primary btn-lg px-4">Downloads</a>
		<a href="https://docs.th.mrms.cz/dl/" class="btn btn-outline-secondary btn-lg px-4 gap-3">Documentation</a>
	  </div>
	</div>
</div>

<div class="container px-4 py-5" id="featured-3">
	<div class="row g-4 py-5 row-cols-1 row-cols-lg-3">
		<div class="feature col">
			<h3 class="fs-2">Made for programmers</h3>
			<p>
				Tophat allows you to do everything programatically and doesn't
				force you to work with annoying editors.  However if you need
				to do a lot of editing you can use
				<a href="https://git.sr.ht/~mrms/proped">PropEd</a>, or make your own
				specialized editor.
			</p>
			<a href="https://docs.th.mrms.cz" class="icon-link d-inline-flex align-items-center">
				Learn about the API
			</a>
		</div>
		<div class="feature col">
			<h3 class="fs-2">Modular design</h3>
			<p>
				Tophat includes many built-in modules.  Some are necessary, but
				most of them are optional and just extend the few base ones.
				If you don't like some of them, you can implement your own
				ones using native C extensions.
			</p>
			<a href="https://git.sr.ht/~mrms/tophat/tree/main/item/examples/extensions" class="icon-link d-inline-flex align-items-center">
				Learn about extensions
			</a>
		</div>
		<div class="feature col">
			<h3 class="fs-2">Open Source and hackable</h3>
			<p>
				Tophat's source is open and licensed under BSD-3.  The source
				code is small, under 10k lines (excluding dependencies).
			</p>
			<a href="https://git.sr.ht/~mrms/tophat" class="icon-link d-inline-flex align-items-center">
				Browse the source
			</a>
		</div>
	</div>
</div>

<div class="text-white discord-box pt-5 pb-5 mb-5">
	<div class="container">
		<h2>Join us on Discord.</h2>
		<a href="https://discord.gg/PcT7cn59h9" class="btn btn-outline-light">Join Discord</a>
	</div>
</div>

<div class="container mb-5">
	<h2>Play (with) the examples</h2>
	<div class="row row-cols-1 row-cols-sm-2 row-cols-md-3 g-3">
		<div class="col">
			<div class="card shadow-sm">
				<img class="card-img-top no-aa" widht="100%"
					src="/img/space-shooter.png"
				/>
				<div class="card-body">
					<p class="card-text">
						The space shooter is an arcade game, where you have to
						shoot enemies before they descend down the screen. It shows
						the basics of game development in tophat, featuring things
						like movement, collision handling, particles and GUI.
					</p>
					<div class="d-flex justify-content-between align-items-center">
						<div class="btn-group">
							<a
								href="https://th.mrms.cz/examples/space-shooter"
								class="btn btn-sm btn-outline-secondary"
							>
								Play
							</a>
							<a
								href="https://https://git.sr.ht/~mrms/tophat/tree/main/item/examples/space-shooter"
								class="btn btn-sm btn-outline-secondary"
							>
								View source
							</a>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="col">
			<div class="card shadow-sm">
				<img class="card-img-top no-aa" widht="100%"
					src="/img/tetris.png"
				/>
				<div class="card-body">
					<p class="card-text">
						This is an implementation of a famous block game only using
						the canvas.um module to draw graphics.  It show many ways
						to add special effects to your games.
					</p>
					<div class="d-flex justify-content-between align-items-center">
						<div class="btn-group">
							<a
								href="https://th.mrms.cz/examples/tetris"
								class="btn btn-sm btn-outline-secondary"
							>
								Play
							</a>
							<a
								href="https://https://git.sr.ht/~mrms/tophat/tree/main/item/examples/tetris"
								class="btn btn-sm btn-outline-secondary"
							>
								View source
							</a>
						</div>
					</div>
				</div>
			</div>
		</div>
		<div class="col">
			<div class="card shadow-sm">
				<img class="card-img-top no-aa" widht="100%"
					src="/img/pomodoro.png"
				/>
				<div class="card-body">
					<p class="card-text">
						A pomodoro timer made in tophat.  It features a custom GUI
						system with fancy transitions and nine-patch rect based
						controls.
					</p>
					<div class="d-flex justify-content-between align-items-center">
						<div class="btn-group">
							<a
								href="https://th.mrms.cz/examples/pomodoro"
								class="btn btn-sm btn-outline-secondary"
							>
								Play
							</a>
							<a
								href="https://https://git.sr.ht/~mrms/tophat/tree/main/item/examples/pomodoro"
								class="btn btn-sm btn-outline-secondary"
							>
								View source
							</a>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</div>

<div class="container">
	<div class="row row-cols-1 row-cols-lg-2">
		<div class="col mb-3">
			<h2>Edit your games using PropEd</h2>
			<p>
				PropEd is a customizable editor written in and for tophat. It
				can properties of types configured using Umka. There are
				already type definitions included for tophat's basic types.
			</p>
			<a href="https://git.sr.ht/~mrms/proped" class="btn btn-outline-primary">
				Try PropEd
			</a>
		</div>
		<div class="col">
			<img src="/img/proped.png" class="no-aa" style="width: 100%" />
		</div>
	</div>
</div>
