---
id: c5ed2c44-bcdf-49b6-9d64-c6ab282304a9
blueprint: page
title: 'Pricing Plan'
author: e015e865-99ad-436e-af23-ba95eb068b1f
template: home
updated_by: e015e865-99ad-436e-af23-ba95eb068b1f
updated_at: 1678856972
block_types:
  -
    id: lf9827sv
    template: |-
      <!-- Hero Start -->
          <div class="container-fluid bg-primary py-5 hero-header mb-5" style="background:url({{background_image}})">
              <div class="row py-3">
                  <div class="col-12 text-center">
                      <h1 class="display-3 text-white animated zoomIn">{{title}}</h1>
                      <a href="{{homepage}}" class="h4 text-white">Home</a>
                      <i class="far fa-circle text-white px-2"></i>
                      <a href="" class="h4 text-white">{{title}}</a>
                  </div>
              </div>
          </div>
          <!-- Hero End -->
    type: inside_page_banner
    enabled: true
  -
    id: lf9830i1
    title: 'PRICING PLAN'
    heading: 'We Offer Fair Prices for Dental Treatment'
    description: 'Tempor erat elitr rebum at clita. Diam dolor diam ipsum et tempor sit. Aliqu diam amet diam et eos labore. Clita erat ipsum et lorem et sit, sed stet no labore lorem sit. Sanctus clita duo justo eirmod magna dolore erat amet'
    title_2: 'Call for Appointment'
    phone_number: '+918907289865'
    button_link: 'entry::035efaf2-3446-44b7-86e7-61a0f508dce3'
    button_link_text: Appointment
    template: |-
      <!-- Pricing Start -->
          <div class="container-fluid py-5 wow fadeInUp" data-wow-delay="0.1s">
              <div class="container">
                  <div class="row g-5">
                      <div class="col-lg-5">
                          <div class="section-title mb-4">
                              <h5 class="position-relative d-inline-block text-primary text-uppercase">{{title}}</h5>
                              <h1 class="display-5 mb-0">{{heading}}</h1>
                          </div>
                          <p class="mb-4">{{description}}</p>
                          <h5 class="text-uppercase text-primary wow fadeInUp" data-wow-delay="0.3s">{{title_2}}</h5>
                          <h1 class="wow fadeInUp" data-wow-delay="0.6s">{{phone_number}}</h1>
                      </div>
                      <div class="col-lg-7">
                          <div class="owl-carousel price-carousel wow zoomIn" data-wow-delay="0.9s">
      	                      {{collection:pricing_plans}}  
                              <div class="price-item pb-4">
                                  <div class="position-relative">
                                      <img class="img-fluid rounded-top" src="{{image}}" alt="">
                                      <div class="d-flex align-items-center justify-content-center bg-light rounded pt-2 px-3 position-absolute top-100 start-50 translate-middle" style="z-index: 2;">
                                          <h2 class="text-primary m-0">{{price}}</h2>
                                      </div>
                                  </div>
                                  <div class="position-relative text-center bg-light border-bottom border-primary py-5 p-4">
                                      <h4>{{title}}</h4>
                                      <hr class="text-primary w-50 mx-auto mt-0">
                                      
                                      {{features}}
                                      <div class="d-flex justify-content-between mb-3"><span>{{feature_name}}</span><i class="fa fa-check text-primary pt-1"></i></div>
                                      {{/features}}
                                      
                                      <a href="{{button_link}}" class="btn btn-primary py-2 px-4 position-absolute top-100 start-50 translate-middle">{{button_link_text}}</a>
                                  </div>
                              </div>
                                {{/collection:pricing_plans}}  
                              
                          </div>
                      </div>
                  </div>
              </div>
          </div>
          <!-- Pricing End -->
    type: pricing_plan
    enabled: true
---
