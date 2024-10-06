</div>

<div class="px-4 py-5 my-5 text-center">
	<img class="d-block mx-auto mb-4 no-aa" src="/logo.png" alt="" height="128">
	<h1 class="display-5 fw-bold">Tophat Game Framework</h1>
	<div class="col-lg-6 mx-auto">
	  <p class="lead mb-4">A 2D Framework for making games in <a
		href="https://github.com/vtereshkov/umka-lang">Umka</a></p>
	  <div class="d-grid gap-2 d-sm-flex justify-content-sm-center">
		<a href="#learn-more" class="btn btn-primary btn-lg px-4 gap-3">Learn More</a>
		<a href="https://tophat2d.dev/dl/" class="btn btn-outline-secondary btn-lg px-4">Downloads</a>
		<a href="https://docs.tophat2d.dev/" class="btn btn-outline-secondary btn-lg px-4 gap-3">Documentation</a>
	  </div>
	</div>
</div>

<div class="container px-4 py-5" id="featured-3">
	<div class="row g-4 py-5 row-cols-1 row-cols-lg-3">
		<div class="feature col">
			<h3 id="learn-more" class="fs-2">Made for programmers</h3>
			<p>
                Tophat allows you to easily accomplish everything
                programatically and doesn't force you to work with annoying
                editors. However you can always make your own ad-hoc editor.
			</p>
			<a href="https://docs.tophat2d.dev" class="icon-link d-inline-flex align-items-center">
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
			<a href="https://github.com/tophat2d/tophat/tree/main/demos/extensions" class="icon-link d-inline-flex align-items-center">
				Learn about extensions
			</a>
		</div>
		<div class="feature col">
			<h3 class="fs-2">Open Source and hackable</h3>
			<p>
				Tophat's source is open and licensed under BSD-3.  The source
				code is small, under 10k lines (excluding dependencies).
			</p>
			<a href="https://github.com/tophat2d/tophat" class="icon-link d-inline-flex align-items-center">
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

<div class="container pt-5 pb-5">
    <h2 class="mb-3 text-center">Play (with) the examples</h2>
</div>
<div class="container mb-5">
	<div class="row row-cols-1 row-cols-sm-2 row-cols-md-4 g-3">
		<div class="col">
			<div class="card shadow-sm">
				<img class="card-img-top no-aa" widht="100%"
					src="/img/flappy.png"
				/>
				<div class="card-body">
					<p class="card-text">
                        The well known flappy bird game, written in tophat. It
                        is very small and simple - implemented in just one 300
                        line file.
					</p>
					<div class="d-flex justify-content-between align-items-center">
						<div class="btn-group">
							<a
								href="https://tophat2d.dev/examples/flappy"
								class="btn btn-sm btn-outline-secondary"
							>
								Play
							</a>
							<a
								href="https://github.com/tophat2d/tophat/tree/main/demos/flappy"
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
								href="https://tophat2d.dev/examples/space-shooter"
								class="btn btn-sm btn-outline-secondary"
							>
								Play
							</a>
							<a
								href="https://github.com/tophat2d/tophat/tree/main/demos/space-shooter"
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
								href="https://tophat2d.dev/examples/tetris"
								class="btn btn-sm btn-outline-secondary"
							>
								Play
							</a>
							<a
								href="https://github.com/tophat2d/tophat/tree/main/demos/tetris"
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
				<img class="card-img-top" widht="100%"
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
								href="https://tophat2d.dev/examples/pomodoro"
								class="btn btn-sm btn-outline-secondary"
							>
								Play
							</a>
							<a
								href="https://git.sr.ht/~mrms/tophat/tree/main/item/examples/pomodoro"
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

<div class="container pt-5 pb-5">
    <h2 class="mb-3 text-center">Projects made in tophat</h2>
</div>
<div style="background-color: black; color: white">
    <div class="container">
        <div class="row row-cols-1 row-cols-lg-2 pt-5">
            <div class="col mb-3">
                <h3>SAVESCUM</h3>
                <p>
                    <a href="https://ske.land/savegame">SAVESCUM</a> is a puzzle
                    platformer that's being worked on by Sviatoslav Shatunov (also
                    known as ske). It revolves around saving and resetting the
                    game's state to solve puzzles and get through the levels.
                </p>
                <a href="https://skejeton.itch.io/savescum" class="btn btn-outline-primary">
                    Play the Prologue
                </a>
            </div>
            <div class="col">
                <img src="/img/savescum.png" style="width: 100%" />
            </div>
        </div>
    </div>
</div>
<div style="background-color: #222221; color: white">
    <div class="container">
        <div class="row row-cols-1 row-cols-lg-2 pt-5 pb-5">
            <div class="col mb-3">
                <h3>I ❤︎ FEM</h3>
                <p>
                    A finite element method demo in Umka and tophat made by
                    Vasiliy Tereshkov. This demo models mechanical stresses and
                    deformations in elastic materials and can serve as a
                    tutorial for learning the fundamentals of finite element
                    analysis.
                </p>
                <p>
                    The project is deliberalely kept very simple. It consists of three main parts:
                </p>
                <ul>
                    <li><b>2D editor</b>, a GUI tool for entering plate geometry, constraints and forces, as well as material properties</li>
                    <li><b>Triangulation procedure</b> that computes the Delaunay triangular mesh using the Bowyer-Watson algorithm, with an enhancement to support insertion of plate boundary edges missing from the vanilla triangulation</li>
                    <li><b>Finite element solver</b> that constructs the stiffness matrices for all the mesh triangles, combines them into the global stiffness matrix and solves the linear equations w.r.t. vertex displacements. It also computes the equivalent stresses using the von Mises criterion</li>
                </ul>
                <a href="https://vtereshkov.github.io/fem/" class="btn btn-primary">
                    Try Online
                </a>
                <a href="https://github.com/vtereshkov/fem" class="btn btn-outline-primary">
                    Source Code
                </a>
            </div>
            <div class="col">
                <img src="/img/fem3.gif" style="width: 100%" />
            </div>
        </div>
    </div>
</div>
<div style="background-color: #757272; color: white">
    <div class="container">
        <div class="row row-cols-1 row-cols-lg-2 pb-5 pt-5">
            <div class="col mb-3">
                <h3>Money, please!</h3>
                <p>
                    <strong>Money, please!</strong> is a fast-paced item
                    flipping game inspired by <em>Papers, Please</em>, created
                    during the GMTK Jam by <a href="https://ske.land"
                    target="_blank">skejeton</a>. Players must buy, sell, and
                    trade items to earn enough profit to pay the rent and avoid
                    eviction.
                </p>
                <a href="https://skejeton.itch.io/moneyplease" class="btn btn-primary">
                    Play the Game
                </a>
            </div>
            <div class="col">
                <img src="/img/moneyplease.png" style="width: 100%" />
            </div>
        </div>
    </div>
</div>
<div style="background-color: black; color: white">
    <div class="container">
        <div class="row row-cols-1 row-cols-lg-2 pt-5 pb-5">
            <div class="col">
                <img src="/img/spacesim.png" style="width: 100%" />
            </div>
            <div class="col mb-3">
                <h3>Space Simulator</h3>
                <p>
                    A 3D orbital rendez-vous and docking simulation made with
                    Umka and Tophat. It uses a custom software renderer written
                    in pure Umka, with Tophat as a 2D drawing backend.
                </p>
                <a href="https://vtereshkov.github.io/space-sim/" class="btn btn-primary">
                    Try Online
                </a>
                <a href="https://github.com/vtereshkov/space-sim" class="btn btn-outline-primary">
                    Source Code
                </a>
            </div>
        </div>
    </div>
</div>
<div style="background-color: #488e51; color: white">
    <div class="container">
        <div class="row row-cols-1 row-cols-lg-2 pt-5 pb-5">
            <div class="col">
                <img src="/img/rail.png" style="width: 100%" />
            </div>
            <div class="col mb-3">
                <h3>Rail dispatcher game</h3>
                <p>
                    This game is about dispatching trains at a 1920's train
                    station in Czechoslovakia. You need to make sure trains run
                    at schedule and, most importantly, don't crash into each
                    other. The source code for the game is yet to be released,
                    but I've been creating a series of 
                    <a href="https://mrms.cz/game" style="color:
                    #80c668">development logs</a>.
                </p>
            </div>
        </div>
    </div>
</div>
