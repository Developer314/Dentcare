---
id: 6f980919-0888-4161-8085-0a512f8f4922
blueprint: page
title: About
author: e015e865-99ad-436e-af23-ba95eb068b1f
template: home
updated_by: e015e865-99ad-436e-af23-ba95eb068b1f
updated_at: 1678856547
block_types:
  -
    id: lf97tqnc
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
    id: lf97twxk
    title: 'About Us'
    heading_1: "The World's Best Dental Clinic That You Can Trust"
    heading_2: 'Diam dolor diam ipsum sit. Clita erat ipsum et lorem stet no lorem sit clita duo justo magna dolore'
    description: 'Tempor erat elitr rebum at clita. Diam dolor diam ipsum et tempor sit. Aliqu diam amet diam et eos labore. Clita erat ipsum et lorem et sit, sed stet no labore lorem sit. Sanctus clita duo justo et tempor eirmod magna dolore erat amet'
    paragraph_below: |-
      <div class="row g-3">
                              <div class="col-sm-6 wow zoomIn" data-wow-delay="0.3s">
                                  <h5 class="mb-3"><i class="fa fa-check-circle text-primary me-3"></i>Award Winning</h5>
                                  <h5 class="mb-3"><i class="fa fa-check-circle text-primary me-3"></i>Professional Staff</h5>
                              </div>
                              <div class="col-sm-6 wow zoomIn" data-wow-delay="0.6s">
                                  <h5 class="mb-3"><i class="fa fa-check-circle text-primary me-3"></i>24/7 Opened</h5>
                                  <h5 class="mb-3"><i class="fa fa-check-circle text-primary me-3"></i>Fair Prices</h5>
                              </div>
                          </div>
    image: about.jpg
    button_link: 'entry::c5ed2c44-bcdf-49b6-9d64-c6ab282304a9'
    button_link_text: 'Make Appointment'
    template: |-
      <!-- About Start -->
          <div class="container-fluid py-5 wow fadeInUp" data-wow-delay="0.1s">
              <div class="container">
                  <div class="row g-5">
                      <div class="col-lg-7">
                          <div class="section-title mb-4">
                              <h5 class="position-relative d-inline-block text-primary text-uppercase">{{title}}</h5>
                              <h1 class="display-5 mb-0">{{heading_1}}</h1>
                          </div>
                          <h4 class="text-body fst-italic mb-4">{{heading_2}}</h4>
                          <p class="mb-4">{{description}}</p>
                         {{paragraph_below}}
                          <a href="{{button_link}}" class="btn btn-primary py-3 px-5 mt-4 wow zoomIn" data-wow-delay="0.6s">{{button_link_text}}</a>
                      </div>
                      <div class="col-lg-5" style="min-height: 500px;">
                          <div class="position-relative h-100">
                              <img class="position-absolute w-100 h-100 rounded wow zoomIn" data-wow-delay="0.9s" alt="{{heading_1}}" src="{{image}}" style="object-fit: cover;">
                          </div>
                      </div>
                  </div>
              </div>
          </div>
          <!-- About End -->
    type: about_us
    enabled: true
---
