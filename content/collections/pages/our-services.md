---
id: fdbe0feb-c74e-49bf-81e8-906cd63ec95f
blueprint: page
title: 'Our Services'
author: e015e865-99ad-436e-af23-ba95eb068b1f
template: home
block_types:
  -
    id: lfuk8ouz
    image_before: service-1.jpg
    image_after: service-2.jpg
    title_1: 'Our Services'
    title_2: 'We Offer The Best Quality Dental Services'
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
  -
    id: lfuk9ipc
    background_image: testimonial-1.jpg
    template: |-
      <!-- Testimonial Start -->
          <div class="container-fluid bg-primary bg-testimonial py-5 my-5 wow fadeInUp" style="background:url({{background_image}})" data-wow-delay="0.1s">
              <div class="container py-5">
                  <div class="row justify-content-center">
                      <div class="col-lg-7">
                          <div class="owl-carousel testimonial-carousel rounded p-5 wow zoomIn" data-wow-delay="0.6s">
      	                    
      	                    {{collection:testimonials}}
                              <div class="testimonial-item text-center text-white">
                                  <img class="img-fluid mx-auto rounded mb-4" src="{{client_image}}" alt="{{title}}">
                                  {{testimonial}}
                                  <hr class="mx-auto w-25">
                                  <h4 class="text-white mb-0">{{title}}</h4>
                              </div>
                              {{/collection:testimonials}}
                          </div>
                      </div>
                  </div>
              </div>
          </div>
          <!-- Testimonial End -->
    type: testimonial
    enabled: true
  -
    id: lfukab48
    title: 'OUR DENTIST'
    heading: 'Meet Our Certified & Experienced Dentist'
    button_link: 'entry::e10495c5-6eca-433b-86a3-bd11c091eb54'
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
updated_by: e015e865-99ad-436e-af23-ba95eb068b1f
updated_at: 1680147253
---
