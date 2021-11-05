<template>
  <div>
<!-- PRELOADER -->
	<div id="preloader">
		<div class="loader_line"></div>
	</div>
	<!-- /PRELOADER -->
    <!-- WRAPPER ALL -->
	<div class="myfolio__all_wrap" data-magic-cursor="show" data-color="brown">
<!-- TOPBAR -->
		<div class="myfolio__topbar">
			<div class="topbar_inner">
				<div class="logo">
					<nuxt-link to="/"><img src="/img/logo/dark.png" alt="" /></nuxt-link>
				</div>
				<div class="menu">
					<div class="list">
						<ul class="anchor_nav">
							<li class="current"><a href="#home">Home</a></li>
							<li><a href="#about">About</a></li>
							<li><a href="#service">Services</a></li>
							<li><a href="#portfolio">Portfolio</a></li>
							<li><a href="#news">News</a></li>
							<li><a href="#contact">Contact</a></li>
						</ul>
					</div>
					<div class="trigger">
						<div class="hamburger hamburger--slider">
							<div class="hamburger-box">
								<div class="hamburger-inner"></div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- /TOPBAR -->

    	<!-- MOBILE MENU -->
		<div class="myfolio__mobile_menu">
			<div class="mobile_menu_inner">
				<div class="mobile_in">
					<div class="logo">
						<a href="#"><img src="/img/logo/dark.png" alt="" /></a>
					</div>
					<div class="trigger">
						<div class="hamburger hamburger--slider">
							<div class="hamburger-box">
								<div class="hamburger-inner"></div>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="dropdown">
				<div class="dropdown_inner">
					<ul class="anchor_nav">
						<li class="active"><a href="#home">Home</a></li>
						<li><a href="#about">About</a></li>
						<li><a href="#service">Services</a></li>
						<li><a href="#portfolio">Portfolio</a></li>
						<li><a href="#news">News</a></li>
						<li><a href="#contact">Contact</a></li>
					</ul>
				</div>
			</div>
		</div>
		<!-- /MOBILE MENU -->

    <!-- HERO -->
		<div class="myfolio__section" id="home">
			<div class="myfolio__hero">
				<div class="container">
					<div class="content">
						<div class="texts">
							<div class="job">
								<video playsinline autoplay muted loop>
									<source src="/video/1.mp4" type="video/mp4">
								</video>
								<h3>Senior Designer<br /> &amp; Developer</h3>
							</div>
							<div class="desc">
								<p>Hi, I'm Shadhin Ahmed. A passionate Senior Designer and Front-End Developer based In   v   NYC, USA</p>
							</div>
							<div class="short_skills">
								<div class="text">
									<span>High knowledge on</span>
								</div>
								<div class="icons">
									<ul>
										<li><img class="svg" src="/img/svg/html.svg" alt="" /></li>
										<li><img class="svg" src="/img/svg/css.svg" alt="" /></li>
										<li><img class="svg" src="/img/svg/angular.svg" alt="" /></li>
										<li><img class="svg" src="/img/svg/bootstrap.svg" alt="" /></li>
									</ul>
								</div>
							</div>
						</div>
						<div class="avatar">
							<div class="image" style="background-image:url(/img/shadhin.jpg)"></div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- /HERO -->

    <!-- ABOUT -->
		<div class="myfolio__section" id="about">
			<div class="myfolio__about">
				<div class="container">
					<div class="about_inner">
						<div class="left wow fadeInLeft" data-wow-duration="1.5s">
							<div class="image">
								<img src="img/thumbs/1-1.jpg" alt="" />
								<div class="main" data-img-url="img/about/2.jpg"></div>
								<div class="experience">
									<h3 class="year" data-img-url="img/about/2.jpg">7</h3>
									<div id="circle">
										<svg version="1.1" xmlns="http://www.w3.org/2000/svg"
											xmlns:xlink="http://www.w3.org/1999/xlink" x="0px" y="0px" width="300px"
											height="300px" viewBox="0 0 300 300" enable-background="new 0 0 300 300"
											xml:space="preserve">
											<defs>
												<path id="circlePath"
													d=" M 150, 150 m -60, 0 a 60,60 0 0,1 120,0 a 60,60 0 0,1 -120,0 " />
											</defs>
											<circle cx="150" cy="100" r="75" fill="none" />
											<g>
												<use xlink:href="#circlePath" fill="none" />
												<text fill="#000">
													<textpath xlink:href="#circlePath">Years of best and successful work
														experience</textpath>
												</text>
											</g>
										</svg>
									</div>
								</div>
							</div>
						</div>
						<div class="right wow fadeInRight" data-wow-duration="1.5s">
							<div class="myfolio__title">
								<span>About Me</span>
								<h3>A passionate Senior Designer and Front-End Developer based In NYC, USA</h3>
							</div>
							<div class="text">
								<p>I am passionate Senior Designer, and I'm very passionate and dedicated to my work.
									With 7 years experience as a professional Web developer, I have acquired the skills
									and knowledge necessary to make your project a success.</p>
							</div>
							<div class="signature">
								<img src="img/signature.png" alt="" />
							</div>
							<div class="myfolio__button">
								<a href="#">Download CV</a>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- /ABOUT -->

		<!-- SERVICES -->
		<div class="myfolio__section" id="service">
			<div class="myfolio__services">
				<div class="container">
					<div class="services_inner">
						<div class="left">
							<div class="myfolio__title">
								<span>Services</span>
								<h3>I offer a Full-cycle of Web Development Services</h3>
							</div>
							<div class="text">
								<p>For more than 20 years our experts have been accomplishing enough with modern Web
									Development, new generation programming language, and Full Stack developers to
									deliver cost-effective solutions.</p>
							</div>
							<div class="myfolio_progress">
								<div class="progress_inner" data-value="95">
									<span><span class="label">HTML &amp; CSS</span><span
											class="number">95%</span></span>
									<div class="background">
										<div class="bar">
											<div class="bar_in"></div>
										</div>
									</div>
								</div>
								<div class="progress_inner" data-value="80">
									<span><span class="label">JavaScript</span><span class="number">80%</span></span>
									<div class="background">
										<div class="bar">
											<div class="bar_in"></div>
										</div>
									</div>
								</div>
								<div class="progress_inner" data-value="90">
									<span><span class="label">WordPress</span><span class="number">90%</span></span>
									<div class="background">
										<div class="bar">
											<div class="bar_in"></div>
										</div>
									</div>
								</div>
							</div>
						</div>
						<div class="right">
							<ul class="grid">
								<li class="grid-item wow fadeInUp" data-wow-duration="1.5s">
									<div class="list_inner">
										<img class="svg" src="img/svg/design.svg" alt="" />
										<h3 class="title">Design</h3>
									</div>
								</li>
								<li class="grid-item wow fadeInUp" data-wow-duration="1.5s" data-wow-delay="0.2s">
									<div class="list_inner">
										<img class="svg" src="img/svg/code.svg" alt="" />
										<h3 class="title">Development</h3>
									</div>
								</li>
								<li class="grid-item wow fadeInUp" data-wow-duration="1.5s" data-wow-delay="0.2s">
									<div class="list_inner">
										<img class="svg" src="img/svg/award.svg" alt="" />
										<h3 class="title">Quality</h3>
									</div>
								</li>
								<li class="grid-item wow fadeInUp" data-wow-duration="1.5s">
									<div class="list_inner">
										<img class="svg" src="img/svg/tools.svg" alt="" />
										<h3 class="title">Maintain</h3>
									</div>
								</li>
							</ul>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- /SERVICES -->

		<!-- PORTFOLIO -->
		<div class="myfolio__section" id="portfolio">
			<div class="myfolio__portfolio">
				<div class="container">
					<div class="portfolio_inner">
						<div class="myfolio__title">
							<span>Portfolio</span>
							<h3>Each project is a unique piece of development</h3>
						</div>
						<div class="portfolio_list">
							<ul class="gallery_zoom">
								<li class="wow fadeInUp" data-wow-duration="1.5s">
									<div class="list_inner">
										<div class="image">
											<img src="img/thumbs/1-1.jpg" alt="" />
											<div class="main" data-img-url="img/portfolio/1.jpg"></div>
										</div>
										<div class="overlay"></div>
										<div class="details">
											<h3>Water Drops</h3>
											<span>Vimeo</span>
										</div>
										<a class="myfolio__full_link popup-vimeo"
											href="https://vimeo.com/312334044"></a>
									</div>
								</li>
								<li class="wow fadeInUp" data-wow-duration="1.5s" data-wow-delay="0.2s">
									<div class="list_inner">
										<div class="image">
											<img src="img/thumbs/1-1.jpg" alt="" />
											<div class="main" data-img-url="img/portfolio/2.jpg"></div>
										</div>
										<div class="overlay"></div>
										<div class="details">
											<h3>Sweet Cherry</h3>
											<span>Youtube</span>
										</div>
										<a class="myfolio__full_link popup-youtube"
											href="https://www.youtube.com/watch?v=Amq-qlqbjYA"></a>
									</div>
								</li>
								<li class="wow fadeInUp" data-wow-duration="1.5s" data-wow-delay="0.4s">
									<div class="list_inner">
										<div class="image">
											<img src="img/thumbs/1-1.jpg" alt="" />
											<div class="main" data-img-url="img/portfolio/3.jpg"></div>
										</div>
										<div class="overlay"></div>
										<div class="details">
											<h3>Red Nike</h3>
											<span>Soundcloud</span>
										</div>
										<a class="myfolio__full_link soundcloude_link mfp-iframe audio"
											href="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/252739311&amp;color=%23ff5500&amp;auto_play=true&amp;hide_related=false&amp;show_comments=true&amp;show_user=true&amp;show_reposts=false&amp;show_teaser=true&amp;visual=true"></a>
									</div>
								</li>
								<li class="wow fadeInUp" data-wow-duration="1.5s">
									<div class="list_inner">
										<div class="image">
											<img src="img/thumbs/1-1.jpg" alt="" />
											<div class="main" data-img-url="img/portfolio/6.jpg"></div>
										</div>
										<div class="overlay"></div>
										<div class="details">
											<h3>Blue Lemon</h3>
											<span>Detail</span>
										</div>
										<a class="myfolio__full_link popup_info" href="#"></a>
									</div>

									<!-- Hidden informations for popup begin -->
									<div class="portfolio_hidden_infos">
										<div class="popup_details">
											<div class="top_image"></div>
											<div class="portfolio_main_title"></div>
											<div class="main_details">
												<div class="textbox">
													<p>The origin of the lemon is unknown, though lemons are thought to
														have first grown in Assam (a region in northeast India),
														northern Burma or China. A genomic study of the lemon indicated
														it was a hybrid between bitter orange and citron.</p>
													<p>The first substantial cultivation of lemons in Europe began in
														Genoa in the middle of the 15th century. The lemon was later
														introduced to the Americas in 1493 when Christopher Columbus
														brought lemon seeds to Hispaniola on his voyages. Spanish
														conquest throughout the New World helped spread lemon seeds.</p>
												</div>
												<div class="detailbox">
													<ul>
														<li>
															<span class="first">Client</span>
															<span>Alvaro Morata</span>
														</li>
														<li>
															<span class="first">Category</span>
															<span><a href="#">Detail</a></span>
														</li>
														<li>
															<span class="first">Date</span>
															<span>March 07, 2021</span>
														</li>
														<li>
															<span class="first">Share</span>
															<ul class="share">
																<li><a href="#"><img class="svg"
																			src="img/svg/social/facebook.svg"
																			alt="" /></a></li>
																<li><a href="#"><img class="svg"
																			src="img/svg/social/twitter.svg"
																			alt="" /></a></li>
																<li><a href="#"><img class="svg"
																			src="img/svg/social/instagram.svg"
																			alt="" /></a></li>
																<li><a href="#"><img class="svg"
																			src="img/svg/social/dribbble.svg"
																			alt="" /></a></li>
																<li><a href="#"><img class="svg"
																			src="img/svg/social/tik-tok.svg"
																			alt="" /></a></li>
															</ul>
														</li>
													</ul>
												</div>
											</div>
											<div class="additional_images">
												<ul>
													<li>
														<div class="list_inner">
															<div class="my_image">
																<img src="img/thumbs/4-2.jpg" alt="" />
																<div class="main" data-img-url="img/portfolio/7.jpg">
																</div>
															</div>
														</div>
													</li>
													<li>
														<div class="list_inner">
															<div class="my_image">
																<img src="img/thumbs/4-2.jpg" alt="" />
																<div class="main" data-img-url="img/portfolio/8.jpg">
																</div>
															</div>
														</div>
													</li>
													<li>
														<div class="list_inner">
															<div class="my_image">
																<img src="img/thumbs/4-2.jpg" alt="" />
																<div class="main" data-img-url="img/portfolio/9.jpg">
																</div>
															</div>
														</div>
													</li>
												</ul>
											</div>
										</div>
									</div>
									<!-- Hidden informations for popup end -->

								</li>
								<li class="wow fadeInUp" data-wow-duration="1.5s" data-wow-delay="0.2s">
									<div class="list_inner">
										<div class="image">
											<img src="img/thumbs/1-1.jpg" alt="" />
											<div class="main" data-img-url="img/portfolio/5.jpg"></div>
										</div>
										<div class="overlay"></div>
										<div class="details">
											<h3>Pantone</h3>
											<span>Image</span>
										</div>
										<a class="myfolio__full_link zoom" href="img/portfolio/5.jpg"></a>
									</div>
								</li>
								<li class="wow fadeInUp" data-wow-duration="1.5s" data-wow-delay="0.4s">
									<div class="list_inner">
										<div class="image">
											<img src="img/thumbs/1-1.jpg" alt="" />
											<div class="main" data-img-url="img/portfolio/4.jpg"></div>
										</div>
										<div class="overlay"></div>
										<div class="details">
											<h3>New Telephone</h3>
											<span>Image</span>
										</div>
										<a class="myfolio__full_link zoom" href="img/portfolio/4.jpg"></a>
									</div>
								</li>
							</ul>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- /PORTFOLIO -->

		<!-- VIDEO -->
		<div class="myfolio__section">
			<div class="myfolio__video">
				<div class="background">
					<div class="image jarallax" data-speed="0" data-img-url="img/hero/1.jpg"></div>
					<div class="overlay"></div>
				</div>
				<div class="content">
					<div class="container">
						<div class="content_inner">
							<span class="rounded"><a class="popup-youtube"
									href="https://www.youtube.com/watch?v=ICr_bOuM9Zo"></a></span>
							<h3 class="text wow fadeInUp" data-wow-duration="1.5s">I am delivering beautiful digital
								products for my clients</h3>
							<div class="myfolio__button wow fadeInUp" data-wow-duration="1.5s" data-wow-delay="0.2s">
								<a class="popup-youtube" href="https://www.youtube.com/watch?v=ICr_bOuM9Zo">Watch
									Video</a>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- /VIDEO -->

		<!-- TESTIMONIALS -->
		<div class="myfolio__section">
			<div class="myfolio__testimonials">
				<div id="grouploop">
					<div class="item-wrap">
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
						<div class="item"><span>Testimonials</span></div>
					</div>
				</div>
				<div class="container">
					<div class="testimonials_list">
						<div class="wrapper owl-carousel">
							<div class="wr_in item">
								<div class="list_inner">
									<ul class="stars">
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
									</ul>
									<div class="text">
										<p>I rarely like to write reviews, but the developer truly deserve a standing
											ovation for their customer support, customisation and most importantly,
											friendliness and professionalism. Very satisfying!!!</p>
									</div>
									<div class="details">
										<h3 class="author"><span>Albert Einstein</span></h3>
										<h3 class="job"><span>Freelancer</span></h3>
									</div>
									<div class="avatar">
										<div class="image" data-img-url="img/about/2.jpg"></div>
									</div>
									<img class="svg myquote" src="img/svg/quote.svg" alt="" />
								</div>
							</div>
							<div class="wr_in item">
								<div class="list_inner">
									<ul class="stars">
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
									</ul>
									<div class="text">
										<p>The quality of the design is very high, and with a bit of knowledge about
											HTML and CSS also very easy to customize. Overall a good design, that I am
											quite happy with. Really appreciate that.</p>
									</div>
									<div class="details">
										<h3 class="author"><span>Avon Smith</span></h3>
										<h3 class="job"><span>Designer</span></h3>
									</div>
									<div class="avatar">
										<div class="image" data-img-url="img/about/1.jpg"></div>
									</div>
									<img class="svg myquote" src="img/svg/quote.svg" alt="" />
								</div>
							</div>
							<div class="wr_in item">
								<div class="list_inner">
									<ul class="stars">
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
										<li><img class="svg" src="img/svg/star.svg" alt="" /></li>
									</ul>
									<div class="text">
										<p>I had a problem finding something, asked the support team, got a reply and a
											solution within a few minutes. Brilliant support! very happy with the
											website I bought. Thank you developers!!</p>
									</div>
									<div class="details">
										<h3 class="author"><span>Bruce Kennedy</span></h3>
										<h3 class="job"><span>Photographer</span></h3>
									</div>
									<div class="avatar">
										<div class="image" data-img-url="img/about/3.jpg"></div>
									</div>
									<img class="svg myquote" src="img/svg/quote.svg" alt="" />
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- /TESTIMONIALS -->

		<!-- NEWS -->
		<div class="myfolio__section" id="news">
			<div class="myfolio__news">
				<div class="container">
					<div class="myfolio__title">
						<span>News</span>
						<h3>Check out the latest breaking news headlines on development</h3>
					</div>
					<div class="news_list">
						<ul>
							<li class="wow fadeInUp" data-wow-duration="1.5s">
								<div class="list_inner">
									<div class="image">
										<img src="img/thumbs/4-3.jpg" alt="" />
										<div class="main" data-img-url="img/news/1.jpg"></div>
										<a class="myfolio__full_link" href="#"></a>
									</div>
									<div class="details">
										<span>August 15, 2021 <a href="#">Branding</a></span>
										<h3 class="title"><a href="#">Good Travel</a></h3>
									</div>
									<div class="hide_content">
										<div class="descriptions">
											<p class="bigger">Just because we can't get out and about like we normally
												would, doesn’t mean we have to stop taking pictures. There’s still
												plenty you can do, provided you're prepared to use some imagination.
												Here are a few ideas to keep you shooting until normal life resumes.</p>
											<p>Most photographers love to shoot the unusual, and you don’t get much more
												unusual than These Unprecedented Times. Right now everything counts as
												out of the ordinary. There are a number of remarkable things about these
												lockdown days that are worth photographing now so we can remember them
												when it is all over.</p>
											<p>Streets empty that are usually busy are remarkable and can evoke the
												sense of historical pictures from before the invention of the motorcar.
												Other things that are different at the moment will be queues to get into
												stores and the lines marked out on the floor to show how far apart we
												should be.</p>
											<div class="quotebox">
												<p>Most photographers find it hard to see interesting pictures in places
													in which they are most familiar. A trip somewhere new seems always
													exactly what our photography needed, as shooting away from home
													consistently inspires us to new artistic heights.</p>
											</div>
											<p>Pretend everything is new and that you haven’t seen it before, and then
												you will be free to notice the leading lines, the places where one edge
												meets another in delightful geometric harmony, and how the ordinary
												things in the kitchen are transformed when the light is on or off.</p>
											<p>The trick here is to look slowly, and then look again. Take the time to
												look in detail and to look at the same thing from different angles, with
												different light, long lenses and wide lenses. Then move to the left a
												bit. You may never feel the need to leave the house again.</p>
										</div>
									</div>
								</div>
							</li>
							<li class="wow fadeInUp" data-wow-duration="1.5s" data-wow-delay="0.2s">
								<div class="list_inner">
									<div class="image">
										<img src="img/thumbs/4-3.jpg" alt="" />
										<div class="main" data-img-url="img/news/2.jpg"></div>
										<a class="myfolio__full_link" href="#"></a>
									</div>
									<div class="details">
										<span>July 25, 2021 <a href="#">Design</a></span>
										<h3 class="title"><a href="#">National Geographic</a></h3>
									</div>
									<div class="hide_content">
										<div class="descriptions">
											<p class="bigger">Just because we can't get out and about like we normally
												would, doesn’t mean we have to stop taking pictures. There’s still
												plenty you can do, provided you're prepared to use some imagination.
												Here are a few ideas to keep you shooting until normal life resumes.</p>
											<p>Most photographers love to shoot the unusual, and you don’t get much more
												unusual than These Unprecedented Times. Right now everything counts as
												out of the ordinary. There are a number of remarkable things about these
												lockdown days that are worth photographing now so we can remember them
												when it is all over.</p>
											<p>Streets empty that are usually busy are remarkable and can evoke the
												sense of historical pictures from before the invention of the motorcar.
												Other things that are different at the moment will be queues to get into
												stores and the lines marked out on the floor to show how far apart we
												should be.</p>
											<div class="quotebox">
												<p>Most photographers find it hard to see interesting pictures in places
													in which they are most familiar. A trip somewhere new seems always
													exactly what our photography needed, as shooting away from home
													consistently inspires us to new artistic heights.</p>
											</div>
											<p>Pretend everything is new and that you haven’t seen it before, and then
												you will be free to notice the leading lines, the places where one edge
												meets another in delightful geometric harmony, and how the ordinary
												things in the kitchen are transformed when the light is on or off.</p>
											<p>The trick here is to look slowly, and then look again. Take the time to
												look in detail and to look at the same thing from different angles, with
												different light, long lenses and wide lenses. Then move to the left a
												bit. You may never feel the need to leave the house again.</p>
										</div>
									</div>
								</div>
							</li>
							<li class="wow fadeInUp" data-wow-duration="1.5s" data-wow-delay="0.4s">
								<div class="list_inner">
									<div class="image">
										<img src="img/thumbs/4-3.jpg" alt="" />
										<div class="main" data-img-url="img/news/3.jpg"></div>
										<a class="myfolio__full_link" href="#"></a>
									</div>
									<div class="details">
										<span>June 02, 2021 <a href="#">Nature</a></span>
										<h3 class="title"><a href="#">Famous Lake</a></h3>
									</div>
									<div class="hide_content">
										<div class="descriptions">
											<p class="bigger">Just because we can't get out and about like we normally
												would, doesn’t mean we have to stop taking pictures. There’s still
												plenty you can do, provided you're prepared to use some imagination.
												Here are a few ideas to keep you shooting until normal life resumes.</p>
											<p>Most photographers love to shoot the unusual, and you don’t get much more
												unusual than These Unprecedented Times. Right now everything counts as
												out of the ordinary. There are a number of remarkable things about these
												lockdown days that are worth photographing now so we can remember them
												when it is all over.</p>
											<p>Streets empty that are usually busy are remarkable and can evoke the
												sense of historical pictures from before the invention of the motorcar.
												Other things that are different at the moment will be queues to get into
												stores and the lines marked out on the floor to show how far apart we
												should be.</p>
											<div class="quotebox">
												<p>Most photographers find it hard to see interesting pictures in places
													in which they are most familiar. A trip somewhere new seems always
													exactly what our photography needed, as shooting away from home
													consistently inspires us to new artistic heights.</p>
											</div>
											<p>Pretend everything is new and that you haven’t seen it before, and then
												you will be free to notice the leading lines, the places where one edge
												meets another in delightful geometric harmony, and how the ordinary
												things in the kitchen are transformed when the light is on or off.</p>
											<p>The trick here is to look slowly, and then look again. Take the time to
												look in detail and to look at the same thing from different angles, with
												different light, long lenses and wide lenses. Then move to the left a
												bit. You may never feel the need to leave the house again.</p>
										</div>
									</div>
								</div>
							</li>
						</ul>
					</div>
				</div>
			</div>
		</div>
		<!-- /NEWS -->

		<!-- CONTACT -->
		<div class="myfolio__section" id="contact">
			<div class="myfolio__contact">
				<div class="container">
					<div class="myfolio__title">
						<span>Contact</span>
						<h3>Feel free to contact me if any assistance is needed in the future</h3>
					</div>
					<div class="short_info wow fadeInUp" data-wow-duration="1.5s">
						<ul>
							<li>
								<div class="list_inner">
									<div class="logo">
										<img class="svg" src="img/svg/location-2.svg" alt="" />
									</div>
									<div class="info">
										<h3>Location</h3>
										<span>123 Ave street, USA</span>
									</div>
								</div>
							</li>
							<li>
								<div class="list_inner">
									<div class="logo">
										<img class="svg" src="img/svg/telephone-2.svg" alt="" />
									</div>
									<div class="info">
										<h3>Phone</h3>
										<span>+77 022 155 02 02</span>
									</div>
								</div>
							</li>
							<li>
								<div class="list_inner">
									<div class="logo">
										<img class="svg" src="img/svg/email-2.svg" alt="" />
									</div>
									<div class="info">
										<h3>Mail</h3>
										<span><a href=""
												class="__cf_email__"
												data-cfemail="2052594b455260474d41494c0e434f4d">[email&#160;protected]</a></span>
									</div>
								</div>
							</li>
						</ul>
					</div>
					<div class="wrapper">
						<div class="left wow fadeInUp" data-wow-duration="1.5s">
							<div class="fields">
								<form action="/" method="post" class="contact_form"
									id="contact_form">
									<div class="returnmessage"
										data-success="Your message has been received, We will contact you soon."></div>
									<div class="empty_notice"><span>Please Fill Required Fields</span></div>
									<div class="first">
										<ul>
											<li>
												<input id="name" type="text" placeholder="Name" autocomplete="off">
											</li>
											<li>
												<input id="email" type="text" placeholder="Email" autocomplete="off">
											</li>
										</ul>
									</div>
									<div class="last">
										<textarea id="message" placeholder="Message"></textarea>
									</div>
									<div class="myfolio__button" data-color="dark">
										<a id="send_message" href="#">Send Message</a>
									</div>

									<!-- If you want change mail address to yours, just open "modal" folder >> contact.php and go to line 4 and change detail to yours.  -->

								</form>
							</div>
						</div>
						<div class="right wow fadeInUp" data-wow-duration="1.5s" data-wow-delay="0.2s">
							<div class="map_wrap">
								<div class="map" id="ieatmaps"></div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- /CONTACT -->

		<!-- COPYRIGHT -->
		<div class="myfolio__section">
			<div class="myfolio__copyright">
				<div class="container">
					<div class="copyright_inner">
						<div class="text wow fadeInLeft" data-wow-duration="1.5s">
							<p>Copyright &copy; 2021. All rights are reserved</p>
						</div>
						<div class="social wow fadeInRight" data-wow-duration="1.5s">
							<ul>
								<li><a href="#"><img class="svg" src="img/svg/social/facebook.svg" alt="" /></a></li>
								<li><a href="#"><img class="svg" src="img/svg/social/twitter.svg" alt="" /></a></li>
								<li><a href="#"><img class="svg" src="img/svg/social/instagram.svg" alt="" /></a></li>
								<li><a href="#"><img class="svg" src="img/svg/social/dribbble.svg" alt="" /></a></li>
								<li><a href="#"><img class="svg" src="img/svg/social/tik-tok.svg" alt="" /></a></li>
							</ul>
						</div>
					</div>
				</div>
			</div>
		</div>
		<!-- /COPYRIGHT -->

		<!-- AUDIO FOR CLICK -->
		<audio id="audio1">
			<source src="audio/1.mp3">
		</audio>
		<audio id="audio2">
			<source src="audio/2.mp3">
		</audio>
		<audio id="audioWind">
			<source src="audio/wind.mp3">
		</audio>
		<!-- /AUDIO FOR CLICK -->

		<!-- MAGIC CURSOR -->
		<div class="mouse-cursor cursor-outer"></div>
		<div class="mouse-cursor cursor-inner"></div>
		<!-- /MAGIC CURSOR -->

  </div>
	<!-- / WRAPPER ALL -->

  </div>
</template>

<script>


  export default {
    head(){
      return {

      }
    },
    beforeMount() {
      myfolio__my_load();
    },
    mounted(){

      myfolio__init__data_load();

      myfolio__nav_bg();
      myfolio__trigger_menu();
      myfolio__modalbox_news();
      myfolio__modalbox_portfolio();
      myfolio__cursor();
      myfolio__imgtosvg();
      myfolio__popup();
      myfolio__data_images();
      myfolio__contact_form();
      myIsotope();
      myfolio__jarallax();
      myfolio__owl_carousel();

    }
  }
</script>

<style scoped>

</style>
