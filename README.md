# mobile-sidebar-navigation
One of the best design strategies you can have while developing a website is "How will this look on mobile?"

From font choices to overall page structure, going from a full-sized desktop display to a much smaller mobile screen can radically shape how your website appears to visitors. If your website visitors can't clearly navigate through your website on their phones, your organization could be losing out on business.

## Tutorial		  
For detailed instructions, view <a href="https://www.solodev.com/blog/web-design/how-to-make-your-sidebar-navigation-mobile-responsive.stml">How to Make Your Sidebar Navigation Mobile Responsive</a> article.
 
## Demo
  		  
Try out a working example on <a href="https://jsfiddle.net/solodev/5uy31hbg/">JSFiddle</a>.

## HTML

The tutorial contains the following basic HTML markup.

```
<div class="container">
	<div class="row">
		<div class="col-sm-12 hidden-lg hidden-md visible-sm visible-xs">
			<select id="sub-menu" name="sub-menu">
				<option>Navigate to...</option>
				<option value="https://www.solodev.com/blog">Blog</option>
				<option value="https://www.solodev.com/product/create.stml">Create Your Website</option>
				<option value="https://www.solodev.com/product/host.stml">Secure Cloud Hosting</option>
				<option value="https://www.solodev.com/product/host.stml">Engage Your Audience</option>
				<option value="https://www.solodev.com/product/support.stml">Support</option>
			</select>
		</div>
	</div>
</div>

<div class="container">
	<div class="row">
		<aside class="sidebar col-lg-3 col-md-4 col-xs-12 mb-5">
			<div class="dynamicDiv" id="dd.0.4.0">
				<div class="sidebar-wrapper">
					<nav>
						<ul class="nolist hidden-sm hidden-xs">
							<li><a href="https://www.solodev.com/blog/">Blog</a></li>
							<li><a href="https://www.solodev.com/product/create.stml">Create Your Website</a></li>
							<li><a href="https://www.solodev.com/product/host.stml">Secure Cloud Hosting</a></li>
							<li><a href="https://www.solodev.com/product/engage.stml">Engage Your Audience</a></li>
							<li><a href="https://www.solodev.com/product/support.stml">Support</a></li>
						</ul>
					</nav>
				</div><!-- .sidebar-wrapepr -->
			</div>
		</aside>
		<div class="content col-lg-9 col-md-8 col-xs-12">
			<div class="dynamicDiv" id="dd.0.4.1"></div>
			<article>
				<div class="row">
					<div class="col-sm-12">
						<h2>Adding Mobile Responsiveness to your Sidebar Navigation</h2>
					</div>
				</div>
				<div class="row">
					<div class="col-sm-12">
						<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
						<p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt.</p>
						<p>Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?</p>
					</div>
				</div>
			</article>
		</div>
	</div>
</div>         
```

## CSS

All required CSS is contained with style.css

## CSS

All required JS is contained with main.js

## External Resources

This tutorial includes the following third party resources.

```
<link href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css" rel="stylesheet">
<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<script src="https://jsfiddle.net/solodev/5uy31hbg/37/https//maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
```


