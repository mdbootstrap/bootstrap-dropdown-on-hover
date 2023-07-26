# Dropdown on hover

Responsive Dropdown on hover built with Bootstrap 5. Example of how to make dropdown expand when you hover over it.

Check out [Bootstrap Dropdown on hover Documentation](https://mdbootstrap.com/docs/standard/extended/dropdown-on-hover/) for detailed instructions & even more examples.

## Basic example

Add `CSS` that makes the dropdown-menu expand when hovering over a dropdown element.

```html
<div class="dropdown">
  <button
    class="btn btn-primary dropdown-toggle"
    type="button"
    id="dropdownMenuButton"
    data-mdb-toggle="dropdown"
    aria-expanded="false"
  >
    Dropdown button
  </button>
  <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
    <li><a class="dropdown-item" href="#">Action</a></li>
    <li><a class="dropdown-item" href="#">Another action</a></li>
    <li><a class="dropdown-item" href="#">Something else here</a></li>
  </ul>
</div>
```

```css
.dropdown:hover>.dropdown-menu {
  display: block;
}

.dropdown>.dropdown-toggle:active {
  /*Without this, clicking will make it sticky*/
    pointer-events: none;
}
```


## How to use?

1. Download MDB - free UI KIT

2. Choose your favorite customized component and click on the image

3. Copy & paste the code into your MDB project

[▶️ Subscribe to the YouTube channel for web development tutorials & resources](https://www.youtube.com/MDBootstrap?sub_confirmation=1)



___

## More extended Bootstrap documentation
<ul>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-address-form/">Address Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/avatar/">Avatar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/back-to-top/">Scroll Back To Top button</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/carousel-with-thumbnails/">Bootstrap Carousel Slider with Thumbnails</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bullet-list/">Bullet list</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/chat/">Chat</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/code/">Code </a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/comments/">Comments</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-comparison-table/">Comparison table</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/credit-card/">Credit card form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/drawer/">Drawer</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-multilevel/">Nested Dropdown</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/faq/">FAQ component / section</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/gallery/">Gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/hamburger-menu/">Hamburger Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-invoice/">Invoice</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/jumbotron/">Jumbotron</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/login/">Login form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/maps/">Maps</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/media-object/">Media object</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/mega-menu/">Mega Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/multiselect/">Multiselect</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/news-feed/">News feed</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/offcanvas/">Offcanvas</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/order-details/">Order details</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/page-transitions/">Page transitions</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/payment-forms/">Payment Forms</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/product-cards/">Product Cards</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/profiles/">Profiles</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/quotes/">Quotes</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/registration/">Registration form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/search-expanding/">Expanding Search Bar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/select-with-custom-input/">Select with custom Input</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/shopping-carts/">Shopping carts</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/side-navbar/">Side Navbar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/sidebar/">Sidebar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/social-media/">Social Media icons & buttons</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/square-buttons/">Square Buttons</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-survey-form/">Survey form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonial-slider/">Testimonial Slider</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonials/">Testimonials / Reviews</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/textarea/">Textarea</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/css-text-animations/">Text animations</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/timeline/">Timeline</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/to-do-list/">To Do List</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/video/">Video carousel / gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/video-carousel/">Video carousel / gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/weather/">Weather</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dark-mode/">Dark mode</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/padding/">Padding</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/modal-size/">Modal Size</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/modal-methods/">Modal Show, Close, Hide & Toggle</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/modal-backdrop/">Modal Backdrop</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/card-columns/">Card Deck</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/card-deck/">Card Deck</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/table-filter/">Table Filter</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/table-responsive/">Table responsive</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/slider/">Slider</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/slideshow/">Slideshow</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/logo/">Logo</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/popup/">Popup</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/max-width/">Max Width</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/hero/">Hero</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/inline-list/">Inline list</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/select-dropdown/">Select Dropdown</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/labels/">Labels</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dialog/">Dialog</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/screen-sizes/">Screen Sizes</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-button/">Dropdown Button</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/widgets/">Widgets</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/overlay/">Overlay</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/height/">Height</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/popover-on-hover/">Popover on hover</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/border-radius/">Border radius</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/table-fixed-header/">Table fixed header</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/side-menu/">Side menu</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/vertical-navbar/">Vertical navbar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/flash-messages/">Flash messages</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/number-inputs/">Number inputs</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/inline-block/">Inline block</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/modal-form/">Modal form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/horizontal-list/">Horizontal list</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/side-panel/">Side panel</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/navbar-brand/">Navbar brand</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/select-list/">Select list</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/cookie-consent/">Cookie consent</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/table-column-width/">Table column width</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-language-selector/">Dropdown language selector</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/select-dropdown-with-search/">Select dropdown with search</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/icon-color/">Icon color</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/fade-animation/">Fade animation</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/carousel-autoplay/">Carousel autoplay</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/modal-image/">Modal image</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/navbar-with-icons/">Navbar with icons</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/image-grid/">Image grid</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/fullscreen-background-image/">Fullscreen background image</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/list-with-icons/">List with icons</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/social-media-icons-footer/">Social media icons footer</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/notification-badge/">Notification badge</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/music-player/">Music / Audio player</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/colors-code/">Colors code</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/alert-auto-close/">Alert auto close</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/pie-chart/">Pie chart</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/file-input-image/">File input image</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/calculator/">Calculator</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/responsive-table/">Table collapse expand rows</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/sticky-footer/">Sticky footer</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/icon-size/">Icon size</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-with-notification/">Dropdown with notification</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-checkbox/">Dropdown checkbox</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/button-colors/">Button colors</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/mobile-menu/">Mobile menu</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/text-wrap/">Text wrap</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/small-box/">Small box</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/table-header-color/">Table header color</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/tiles/">Tiles</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/range-slider-with-labels/">Range slider with labels</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/margin/">Margin</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/password-reset-template/">Password reset template</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/text-align-right/">Text align right</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/scroll-div/">Scroll div</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/menu-with-icons/">Menu with icons</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/slide-animation/">Slide animation</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/circle-badge/">Circle badge</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/animated-icons/">Animated icons</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/textarea-scrollbar/">Textarea scrollbar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/empty-row/">Empty row</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/tabs-vertical/">Tabs vertical</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/switch-with-text/">Switch with text</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/break-word/">Break Word</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/table-no-border/">Table no border</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/d-flex-classes/">D-flex classes</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/header-with-logo/">Header with logo</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/icon-inside-input/">Icon inside input</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/datepicker-default-date/">Datepicker default date</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/animations-classes-on-scroll/">Animations classes on scroll</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/modal-hover/">Modal hover</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/horizontal-accordion/">Horizontal accordion</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/product-carousel/">Product carousel</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/phone-number-input-mask/">Phone number input mask</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/line-chart/">Line chart</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/combobox/">Combobox</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/select-styling/">Select styling</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/full-screen-modal/">Full screen modal</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-hover/">Dropdown hover</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/order-form/">Order form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/half-page-background-image/">Half page background image</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/modal-onload/">Modal onload</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bar-chart/">Bar chart</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/custom-play-button/">Custom play button</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/double-navigation-with-2-navbars/">Double navigation with 2 navbars</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/google-maps/">Google maps</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/password-validation/">Password validation</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/progress-bar-with-steps/">Progress bar with steps</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/active-class-in-navbar/">Active class in navbar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/navbar-height/">Navbar height</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/navbar-search/">Navbar search</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/multiselect-modal/">Multiselect modal</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/chart-card/">Chart card</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/cards-list/">Cards list</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/input-group-width/">Input group width</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/horizontal-form/">Horizontal form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/input-and-button-on-same-line/">Input and button on same line</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/social-media-icons-navbar/">Social media icons navbar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/header-with-footer">Header with footer</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/gradient-navbar">Gradient navbar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/doughnut-chart">Doughnut chart</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/checkbox-list-group">Checkbox list group</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/select-dropdown-with-icon">Select dropdown with icon</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-on-hover">Dropdown on hover</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/checkbox-buttons">Checkbox buttons</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/login-form-with-background-image">Login form with background image</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/vertical-carousel">Vertical carousel</a></li>
</ul>