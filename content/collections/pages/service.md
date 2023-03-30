---
id: b268a684-d54b-48cc-aaf3-300e10c6dc84
blueprint: page
title: Service
author: e015e865-99ad-436e-af23-ba95eb068b1f
template: home
updated_by: e015e865-99ad-436e-af23-ba95eb068b1f
updated_at: 1678856706
block_types:
  -
    id: lf97v613
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
    id: lf97v9jb
    title_1: 'Our Services'
    title_2: 'We Offer The Best Quality Dental Services'
    services:
      -
        id: lf97vquf
        title: 'Cosmetic Dentistry'
        image: service-1.jpg
      -
        id: lf97w6ha
        title: 'Cosmetic Dentistry'
        image: service-2.jpg
      -
        id: lf97wbfg
        title: 'Cosmetic Dentistry'
        image: service-3.jpg
      -
        id: lf97wfz7
        title: 'Cosmetic Dentistry'
        image: service-4.jpg
    template: |-
      <!-- Service Start --> 
          <div class="container-fluid py-5 wow fadeInUp" data-wow-delay="0.1s">
              <div class="container">
                  <div class="row g-5 mb-5">
                      <div class="col-lg-5 wow zoomIn" data-wow-delay="0.3s" style="max-height: 400px;">
                          <div class="twentytwenty-container position-relative h-100 rounded overflow-hidden">
                              <img class="position-absolute w-100 h-100" src="{{image_before}}" style="object-fit: cover;">
                              <img class="position-absolute w-100 h-100" src="{{image_after}}" style="object-fit: cover;">
                          </div>
                      </div>
                      <div class="col-lg-7">
                          <div class="section-title mb-5">
                              <h5 class="position-relative d-inline-block text-primary text-uppercase">{{title_1}}</h5>
                              <h1 class="display-5 mb-0">{{title_2}}</h1>
                          </div>
                          <div class="row g-5">
      	                    {{services}}
      	                     <div class="col-md-6 service-item wow zoomIn" data-wow-delay="0.9s">
                                  <div class="rounded-top overflow-hidden">
                                      <img class="img-fluid" src="{{image}}" alt="{{title}}">
                                  </div>
                                  <div class="position-relative bg-light rounded-bottom text-center p-4">
                                      <h5 class="m-0">{{title}}</h5>
                                  </div>
                              </div>
      	                    {{/services}}
                              
                             
                          </div>
                      </div>
                  </div>
                 
              </div>
          </div>
          <!-- Service End -->
    type: our_services
    enabled: true
    image_before: before.jpg
    image_after: after.jpg
---
