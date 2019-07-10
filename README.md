# Introduction Bootstrap

### Add Bootstrap
- Link download bootstrap [CSS, JS](https://getbootstrap.com/docs/4.3/getting-started/download/).
- Link [jQuery](https://code.jquery.com/jquery-3.3.1.slim.js), copy and save it (Ex: jquery.js).
- Link add bootstrap in html of my index
	Add CSS in ```<head>``` tag.
	```html
		<link rel="stylesheet" type="text/css" href="../source/bootstrap4/css/bootstrap.css">
	```
	Add JS, jQuery in the end of ```<body>``` tag.
	```html
		<script src="../source/bootstrap4/js/jquery.js"></script>
		<script src="../source/bootstrap4/js/bootstrap.js"></script>
	```

# Keyword Layout
### **`Containers`**
- container: have margin, padding.
- container-fluid : full.

### **`Response breakpoint`**
 >size
- xs: extra small devices
- sm: small devices
- md: medium devices
- lg: lagre devices
- xl: extra large devices
- auto

### **`Grid`**
- row-*size*
- col-*size*
- justify-content-*
	- start
	- end
	- between
	- around
	- center

### **`Utilities for layout`**
>[Explain more](https://getbootstrap.com/docs/4.3/layout/utilities-for-layout/)

# Color
- transparent
- primary: `#cce5ff`
- secondary: `#e2e3e5`
- success: `#d4edda`
- danger: `#f8d7da`
- warning: `#fff3cd`
- info: `#d1ecf1`
- light: `#fefefe`
- dark: `#d6d8d9`
	```html
	<div class="alert alert-primary" role="alert">
 		 A simple primary alert—check it out!
	</div>
	```


# Keyword Components
>Name class
### **`Alert`**
- alert
- alert-heading 
- alert-link
- alert-*color*
- alert-dismissible
 	>[Explain more](https://getbootstrap.com/docs/4.3/components/alerts/)

### **`Badge`**
- badge
- badge-*color*
- badge-pill : more radius.
	>[Explain more](https://getbootstrap.com/docs/4.3/components/badge/)

### **`Breadcrumb`**
- breadcrumb-item
- active
 	>[Explain more](https://getbootstrap.com/docs/4.3/components/breadcrumb/#changing-the-separator)

### **`Buttons`**
- btn
- btn-*color*
- btn-outline-*color*
- btn-lg
- btn-sm
- btn-block
- out class: disabled
	> ```<a>``` don’t support the disabled attribute, so you must add the .disabled class to make it visually appear disabled.
- active
- btn-group
- btn-group-lg/ btn-group-sm
 	>[Explain more](https://getbootstrap.com/docs/4.3/components/button-group/)

### **`Card`**
- card
- card-header
- card-body
- card-footer
- card-title
- card-text
- card-img-top
- card border-*color*
- card bg-*color*
- card-group
- card-deck

### **`Carousel`**
- id="carouselExampleControls"
- id="carouselExampleSlidesOnly"
- id="carouselExampleIndicators"
- id="carouselExampleCaptions"
- id="carouselExampleFade"
- carousel slide
- carousel-inner
- carousel-item
- active
- carousel-control-prev/next
- carousel-control-prev/next-icon
- carousel-indicators
- carousel-fade
- data-interval="1000"

### **`Collapse`**
- accordian
- id="accordionExample"
 	>Using the card component, you can extend the default collapse behavior to create an accordion. To properly achieve the accordion style, be sure to use .accordion as a wrapper.
---
- collapse
- show
- collapsed
- data-toggle="collapse"
- data-target="#collapseOne"
- aria-expanded="true"
- aria-controls="collapseOne"
---
- id="collapseOne"
- class="collapse show"
- aria-labelledby="headingOne"
- data-parent="#accordionExample"

### **`Dropdown`**
- dropup
- dropleft
- dropright
- dropdown
- dropdown-toggle
- dropdown-toggle-split
---
- id="dropdownMenuButton"
- data-toggle="dropdown"
- aria-haspopup="true"
- aria-expanded="false"
- data-offset="10,20"
---
- dropdown-menu
- dropdown-item
- dropdown-divider
- dropdown-menu-lg-right (align)
- dropdown-header
- disabled / active
- text-muted