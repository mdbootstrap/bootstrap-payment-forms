# Bootstrap Payment Forms

Responsive Payment Forms built with the latest Bootstrap 5. Credit card, PayPal, Stripe, eCommerce checkout and many more examples.

## Basic example

HTML

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

CSS
```css
.btn-group-vertical>.btn:not(:first-child),
.btn-group-vertical>.btn-group:not(:first-child) { margin-top: 0; }
```
