
Responsive Payment Forms built with the latest Bootstrap 5. Credit card, PayPal, Stripe, eCommerce checkout and many more examples.

Check out [Bootstrap Payment Forms Documentation](https://mdbootstrap.com/docs/standard/extended/payment-forms/) for detailed instructions & even more examples.

## Basic example

![Bootstrap 5 Payment Forms](https://mdbootstrap.com/img/Marketing/github/payment-forms/basic.png)

```html
<section>
  <div class="d-flex justify-content-between align-items-center mb-5">
    <div class="d-flex flex-row align-items-center">
      <h4 class="text-uppercase mt-1">Eligible</h4>
      <span class="ms-2 me-3">Pay</span>
    </div>
    <a href="#!">Cancel and return to the website</a>
  </div>

  <div class="row">
    <div class="col-md-7 col-lg-7 col-xl-6 mb-4 mb-md-0">
      <h5 class="mb-0 text-success">$85.00</h5>
      <h5 class="mb-3">Diabites Pump & Supplies</h5>
      <div>
        <div class="d-flex justify-content-between">
          <div class="d-flex flex-row mt-1">
            <h6>Insurance Responsibility</h6>
            <h6 class="fw-bold text-success ms-1">$71.76</h6>
          </div>
          <div class="d-flex flex-row align-items-center text-primary">
            <span class="ms-1">Add Insurer card</span>
          </div>
        </div>
        <p>
          Insurance claim and all neccessary dependencies will be submitted to your
          insurer for the covered portion of this order.
        </p>
        <div
          class="p-2 d-flex justify-content-between align-items-center"
          style="background-color: #eee;"
        >
          <span>Aetna - Open Access</span>
          <span>Aetna - OAP</span>
        </div>
        <hr />
        <div class="d-flex justify-content-between align-items-center">
          <div class="d-flex flex-row mt-1">
            <h6>Patient Balance</h6>
            <h6 class="fw-bold text-success ms-1">$13.24</h6>
          </div>
          <div class="d-flex flex-row align-items-center text-primary">
            <span class="ms-1">Add Payment card</span>
          </div>
        </div>
        <p>
          Insurance claim and all neccessary dependencies will be submitted to your
          insurer for the covered portion of this order.
        </p>
        <div class="d-flex flex-column mb-3">
          <div class="btn-group-vertical" role="group" aria-label="Vertical button group">
            <input
              type="radio"
              class="btn-check"
              name="options"
              id="option1"
              autocomplete="off"
            />
            <label class="btn btn-outline-primary btn-lg" for="option1">
              <div class="d-flex justify-content-between">
                <span>VISA </span>
                <span>**** 5436</span>
              </div>
            </label>

            <input
              type="radio"
              class="btn-check"
              name="options"
              id="option2"
              autocomplete="off"
              checked
            />
            <label class="btn btn-outline-primary btn-lg" for="option2">
              <div class="d-flex justify-content-between">
                <span>MASTER CARD </span>
                <span>**** 5038</span>
              </div>
            </label>
          </div>
        </div>
        <div class="btn btn-success btn-lg btn-block">Proceed to payment</div>
      </div>
    </div>
    <div class="col-md-5 col-lg-4 col-xl-4 offset-lg-1 offset-xl-2">
      <div class="p-3" style="background-color: #eee;">
        <span class="fw-bold">Order Recap</span>
        <div class="d-flex justify-content-between mt-2">
          <span>contracted Price</span> <span>$186.86</span>
        </div>
        <div class="d-flex justify-content-between mt-2">
          <span>Amount Deductible</span> <span>$0.0</span>
        </div>
        <div class="d-flex justify-content-between mt-2">
          <span>Coinsurance(0%)</span> <span>+ $0.0</span>
        </div>
        <div class="d-flex justify-content-between mt-2">
          <span>Copayment </span> <span>+ 40.00</span>
        </div>
        <hr />
        <div class="d-flex justify-content-between mt-2">
          <span class="lh-sm"
            >Total Deductible,<br />
            Coinsurance and copay
          </span>
          <span>$40.00</span>
        </div>
        <div class="d-flex justify-content-between mt-2">
          <span class="lh-sm"
            >Maximum out-of-pocket <br />
            on insurance policy</span
          >
          <span>$40.00</span>
        </div>
        <hr />
        <div class="d-flex justify-content-between mt-2">
          <span>Insurance Responsibility </span> <span>$71.76</span>
        </div>
        <div class="d-flex justify-content-between mt-2">
          <span>Patient Balance </span> <span>$13.24</span>
        </div>
        <hr />
        <div class="d-flex justify-content-between mt-2">
          <span>Total </span> <span class="text-success">$85.00</span>
        </div>
      </div>
    </div>
  </div>
</section>
```

```css
.btn-group-vertical>.btn:not(:first-child),
.btn-group-vertical>.btn-group:not(:first-child) {
   margin-top: 0;
   }
```

## How to use?

1. Download MDB 5 - free UI KIT

2. Choose your favourite customized component and click on the image

3. Copy & paste the code into your MDB project

[▶️ Subscribe to YouTube channel for web development tutorials & resources](https://www.youtube.com/MDBootstrap?sub_confirmation=1)

## More examples

[Bootstrap Ecommerce checkout page:
![Bootstrap 5 Payment Forms](https://mdbootstrap.com/img/Marketing/github/payment-forms/section-2.png)](https://mdbootstrap.com/docs/standard/extended/payment-forms/#section-2)

[Bootstrap Payment card:
![Bootstrap 5 Payment Forms](https://mdbootstrap.com/img/Marketing/github/payment-forms/section-3.png)](https://mdbootstrap.com/docs/standard/extended/payment-forms/#section-3)

[Bootstrap Pricing plan with credit card payment details:
![Bootstrap 5 Payment Forms](https://mdbootstrap.com/img/Marketing/github/payment-forms/section-4.png)](https://mdbootstrap.com/docs/standard/extended/payment-forms/#section-4)

[Bootstrap Credit card payment form:
![Bootstrap 5 Payment Forms](https://mdbootstrap.com/img/Marketing/github/payment-forms/section-5.png)](https://mdbootstrap.com/docs/standard/extended/payment-forms/#section-5)

[Bootstrap Credit card payment form template:
![Bootstrap 5 Payment Forms](https://mdbootstrap.com/img/Marketing/github/payment-forms/section-6.png)](https://mdbootstrap.com/docs/standard/extended/payment-forms/#section-6)

[Bootstrap Payment form:
![Bootstrap 5 Payment Forms](https://mdbootstrap.com/img/Marketing/github/payment-forms/section-7.png)](https://mdbootstrap.com/docs/standard/extended/payment-forms/#section-7)

___

## More extended Bootstrap documentation

<ul>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-address-form/">Bootstrap Address Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/avatar/">Bootstrap Avatar</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/back-to-top/">Bootstrap Back To Top Button</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/carousel-with-thumbnails/">Bootstrap Carousel Slider with Thumbnails</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/chat/">Bootstrap Chat</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/code/">Bootstrap Code Blocks</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/comments/">Bootstrap Comments</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-comparison-table/">Bootstrap Comparison Table</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/credit-card/">Bootstrap Credit Card Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/drawer/">Bootstrap Drawer</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/dropdown-multilevel/">Bootstrap Nested Dropdown</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/faq/">Bootstrap FAQ component / section</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/gallery/">Bootstrap Gallery</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/hamburger-menu/">Bootstrap Hamburger Menu</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-invoice/">Bootstrap Invoice</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/jumbotron/">Bootstrap Jumbotron</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/login/">Bootstrap Login Form</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/maps/">Bootstrap Maps</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/media-object/">Bootstrap Media Object</a></li>
<li><a href="https://mdbootstrap.com/docs/standard/extended/mega-menu/">Bootstrap Mega Menu</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/multiselect/">Bootstrap Multiselect</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/news-feed/">Bootstrap News Feed</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/offcanvas/">Bootstrap Offcanvas</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/order-details/">Bootstrap Order Details</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/page-transitions/">Bootstrap Page Transitions</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/payment-forms/">Bootstrap Payment Forms</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/product-cards/">Bootstrap Product Cards</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/profiles/">Bootstrap Profiles</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/quotes/">Bootstrap Quotes</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/registration/">Bootstrap Registration Form</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/search-expanding/">Bootstrap Expanding Search Bar</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/shopping-carts/">Bootstrap Shopping Carts</a></li> 
<li><a href="https://mdbootstrap.com/docs/standard/extended/side-navbar/">Bootstrap Side Navbar</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/sidebar/">Bootstrap Sidebar</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/social-media/">Bootstrap Social Media Icons & Buttons</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/square-buttons/">Bootstrap Square Buttons</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/bootstrap-survey-form/">Bootstrap Survey Form</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonial-slider/">Bootstrap Testimonial Slider</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/testimonials/">Bootstrap Testimonials</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/textarea/">Bootstrap Textarea</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/timeline/">Bootstrap Timeline</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/to-do-list/">Bootstrap To Do List</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/video-carousel/">Bootstrap Video Carousel / Gallery</a></li>  
<li><a href="https://mdbootstrap.com/docs/standard/extended/weather/">Bootstrap Weather</a></li>  
</ul>

