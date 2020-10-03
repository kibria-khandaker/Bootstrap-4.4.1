# Bootstrap-4.4.1
Bootstrap-4.4.1 class information and others information for making template .

---


```html

  
 


	https://getbootstrap.com/docs/4.4/getting-started/introduction/
	https://getbootstrap.com/docs/4.4/layout/overview/
	-------------------------------------------------------------------------------

	.container		100%	540px	720px	960px	1140px
	.container-sm		100%	540px	720px	960px	1140px
	.container-md		100%	100%	720px	960px	1140px
	.container-lg		100%	100%	100%	960px	1140px
	.container-xl		100%	100%	100%	100%	1140px

	.container-fluid	100%	100%	100%	100%	100% 

	-------------------------------------------------------------------------------
	
	No media query for `xs` since this is the default in Bootstrap,So
	@{ xs }Extra small devices( <576px .col ,portrait phones, less than 576px).
	@media (min-width: 576px) { sm ≥576px  } col-sm-
	@media (min-width: 768px) { md ≥768px  } col-md-
	@media (min-width: 992px) { lg ≥992px  } col-lg-
	@media (min-width: 1200px){ xl ≥1200px } col-xl-    start from .....<

	-------------------------------------------------------------------------------

	-------------------------------------------------------------------------------
	Some Class ....
	
	=> container-fluid , no-gutters , col-md-auto ,
	
	=> .px-lg-5,.mx-lg-n5 ,
	(.col padding with .px-lg-5, counteracted that with .mx-lg-n5 on the parent 
	 .row and then adjusted the .container wrapper with .px-lg-5.)

	-------------------------------------------------------------------------------
	<div class="row align-items-start"> // start, center, end
	<div class="row justify-content-start"> // start, center, end ,around , between

	<div class="col order-12"> // .order-1.order-md-2.... call number value will priority
	<div class="col"> 
	<div class="col order-1"> 
	- Here 12>1>col will show 
	  { example 1)col order-last , 2)col , 3)col order-first } 
	- but result 3) > 2) > 1)

	-------------------------------------------------------------------------------
	class="col-md-4 offset-md-4" , class="col-md-4 offset-4" 
	class="col-md-3 ml-md-auto"  , class="col-md-4 ml-auto" 
	class="col-auto mr-auto" , class="col-auto"

	class="shadow p-3 mb-5 bg-white rounded"
	class="shadow-sm p-3 mb-5 bg-white rounded"
	class="shadow-none p-3 mb-5 bg-light rounded"

	class="w-25" 25%
	class="w-50" 50%
	class="w-auto"

	class="h-25" 25%
	class="h-50" 50%
	class="h-auto"

	class="mw-100"
	class="mh-100"

	class="min-vw-100"
	class="min-vh-100"
	class="vw-100"
	class="vh-100"

	m -t b l r x y -0....5/auto
	p -t b l r x y -0....5/auto

	bd-highlight, text-truncate
	-------------------------------------------------------------------------------
	
	-Please note that vertical-align only affects inline, inline-block, inline-table, and table cell elements.
	-Choose from .align-baseline, .align-top, .align-middle, .align-bottom, .align-text-bottom, and .align-text-top as needed.

	-------------------------------------------------------------------------------

	-------------------------------------------------------------------------------
	<img src="..." class="img-thumbnail" alt="..." > 
	<img src="..." class="rounded float-left" alt="..."> 
	/here All class/- img-fluid, img-thumbnail,rounded mx-auto d-block

	< figure class="figure" >
		< img src="..." class="figure-img img-fluid rounded" alt="..." >
		< figcaption class="figure-caption text-right" >A caption for the above image.< /figcaption >
	< /figure >
	-------------------------------------------------------------------------------
	-Easily clear floats by adding .clearfix to the parent element. Can also be used as a mixin.
	- <h1 class="text-hide" style="background-image: url('...');"> Bootstrap </h1>
	-------------------------------------------------------------------------------

	https://getbootstrap.com/docs/4.4/layout/grid/
	Use the responsive .row-cols-* classes to quickly set the number of columns
	
		<div class="container">
		  <div class="row row-cols-2">
		    <div class="col">Column</div>
		    <div class="col">Column</div>
		    <div class="col">Column</div>
		    <div class="col">Column</div>
		  </div>
		</div>

		<div class="container">
		  <div class="row row-cols-3">
		    <div class="col">Column</div>
		    <div class="col">Column</div>
		    <div class="col">Column</div>
		    <div class="col">Column</div>
		  </div>
		</div>

		<div class="container">
		  <div class="row row-cols-4">
		    <div class="col">Column</div>
		    <div class="col">Column</div>
		    <div class="col">Column</div>
		    <div class="col">Column</div>
		  </div>
		</div>
		<div class="container">
		  <div class="row row-cols-4">
		    <div class="col">Column 3</div>
		    <div class="col">Column 3</div>
		    <div class="col-6">Column 6</div>
		    <div class="col">Column 3</div>
		  </div>
		</div>
		<div class="container">
		  <div class="row row-cols-1 row-cols-sm-2 row-cols-md-4">
		    <div class="col">Column</div>
		    <div class="col">Column</div>
		    <div class="col">Column</div>
		    <div class="col">Column</div>
		  </div>
		</div>
	

	-------------------------------------------------------------------------------
	Some Icon link :--

	1) https://feathericons.com/
	2) https://ionicons.com/
	3) http://demo.amitjakhu.com/dripicons/
	4) https://material.io/resources/icons/?style=outline
	5) https://icons8.com/
	6) https://github.com/danklammer/bytesize-icons
	7) https://fontawesome.com/
	------------------------------------------------------------------------------- 
  
  
  ```
  
  
  
