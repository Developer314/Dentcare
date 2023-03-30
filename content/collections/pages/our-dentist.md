---
id: e10495c5-6eca-433b-86a3-bd11c091eb54
blueprint: page
title: 'Our Dentist'
author: e015e865-99ad-436e-af23-ba95eb068b1f
template: home
updated_by: e015e865-99ad-436e-af23-ba95eb068b1f
updated_at: 1678857025
block_types:
  -
    id: lf98486w
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
    id: lf984bar
    title: 'OUR DENTIST'
    heading: 'Meet Our Certified & Experienced Dentist'
    button_link: 'entry::035efaf2-3446-44b7-86e7-61a0f508dce3'
    button_link_text: Appointment
    template: |-
      <!-- Team Start -->
          <div class="container-fluid py-5">
              <div class="container">
                  <div class="row g-5">
                      <div class="col-lg-4 wow slideInUp" data-wow-delay="0.1s">
                          <div class="section-title bg-light rounded h-100 p-5">
                              <h5 class="position-relative d-inline-block text-primary text-uppercase">{{title}}</h5>
                              <h1 class="display-6 mb-4">{{heading}}</h1>
                              <a href="{{button_link}}" class="btn btn-primary py-3 px-5">{{button_link_text}}</a>
                              
                             
                              
                              
                          </div>
                      </div>
                      
                      
                     
                     
                      
                      {{collection:our_doctors status:in="published|draft"}}
                      
                      
                      <div class="col-lg-4 wow slideInUp" data-wow-delay="0.3s">
                          <div class="team-item">
                              <div class="position-relative rounded-top" style="z-index: 1;">
                                  <img class="img-fluid rounded-top w-100" src="{{doctor_image}}" alt="{{title}}">
                                  <div class="position-absolute top-100 start-50 translate-middle bg-light rounded p-2 d-flex">
      	                            {{social_media}}
                                      <a class="btn btn-primary btn-square m-1" href="{{social_media_url}}" target="_blank"><i class="fab {{social_media_icon}} fw-normal"></i></a>
                                      {{/social_media}}
                                  </div>
                              </div>
                              <div class="team-text position-relative bg-light text-center rounded-bottom p-4 pt-5">
                                  <h4 class="mb-2">{{title}}</h4>
                                  <p class="text-primary mb-0">{{designation}}</p>
                              </div>
                          </div>
                      </div>
                      {{/collection:our_doctors}}
                  </div>
              </div>
          </div>
          <!-- Team End -->
    type: our_dentist
    enabled: true
---
