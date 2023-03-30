---
id: home
blueprint: pages
title: Home
template: home
author: e015e865-99ad-436e-af23-ba95eb068b1f
block_types:
  -
    id: lf7w5qvx
    carousal_items:
      -
        id: lf7w5rrs
        image: carousel-1.jpg
        heading_1: 'KEEP YOUR TEETH HEALTHY'
        heading_2: 'Take The Best Quality Dental Treatment'
        button_1_link: 'entry::035efaf2-3446-44b7-86e7-61a0f508dce3'
        button_1_text: Appointment
        button_2_link: 'entry::aff18efc-b85a-4d79-af14-92bebf5a76ef'
        button_2_text: 'Contact Us'
      -
        id: lf7w9tuy
        image: carousel-2.jpg
        heading_1: 'KEEP YOUR TEETH HEALTHY 2'
        heading_2: 'Take The Best Quality Dental Treatment 2'
        button_1_link: 'entry::e10495c5-6eca-433b-86a3-bd11c091eb54'
        button_1_text: Contact
        button_2_link: 'entry::c5ed2c44-bcdf-49b6-9d64-c6ab282304a9'
        button_2_text: 'See Pricing Plans'
    type: home_carousal
    enabled: true
    home_carousal:
      -
        id: lf7wp2qw
        image: carousel-1.jpg
        heading_1: 'KEEP YOUR TEETH HEALTHY'
        heading_2: 'Take The Best Quality Dental Treatment'
        button_1_link: 'entry::035efaf2-3446-44b7-86e7-61a0f508dce3'
        button_1_text: Appointment
        button_2_link: 'entry::aff18efc-b85a-4d79-af14-92bebf5a76ef'
        button_2_text: 'Contact Us'
      -
        id: lf7wqbxr
        image: carousel-2.jpg
        heading_1: 'KEEP YOUR TEETH HEALTHY 2'
        heading_2: 'Take The Best Quality Dental Treatment'
        button_1_link: 'entry::c5ed2c44-bcdf-49b6-9d64-c6ab282304a9'
        button_1_text: 'Pricing Plan'
        button_2_link: 'entry::62c41548-3890-4058-a6a0-6bf00950f98b'
        button_2_text: Teastimonial
    template: |-
      <!-- Carousel Start -->
          <div class="container-fluid p-0">
              <div id="header-carousel" class="carousel slide carousel-fade" data-bs-ride="carousel">
                  <div class="carousel-inner">
      	            
      	            
      	            
                      {{home_carousal}}
           	<div class="carousel-item {{ if first }} active {{ /if }}">
                          <img class="w-100" src="{{image}}" alt="{{heading_1}}">
                          <div class="carousel-caption d-flex flex-column align-items-center justify-content-center">
                              <div class="p-3" style="max-width: 900px;">
                                  <h5 class="text-white text-uppercase mb-3 animated slideInDown">{{heading_1}}</h5>
                                  <h1 class="display-1 text-white mb-md-4 animated zoomIn">{{heading_2}}</h1>
                                  <a href="{{button_1_link}}" class="btn btn-primary py-md-3 px-md-5 me-3 animated slideInLeft">{{button_1_text}}</a>
                                  <a href="{{button_2_link}}" class="btn btn-secondary py-md-3 px-md-5 animated slideInRight">{{button_2_text}}</a>
                              </div>
                          </div>
                      </div>
           	{{/home_carousal}}
                      
                      
                      
                  </div>
                  <button class="carousel-control-prev" type="button" data-bs-target="#header-carousel"
                      data-bs-slide="prev">
                      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Previous</span>
                  </button>
                  <button class="carousel-control-next" type="button" data-bs-target="#header-carousel"
                      data-bs-slide="next">
                      <span class="carousel-control-next-icon" aria-hidden="true"></span>
                      <span class="visually-hidden">Next</span>
                  </button>
              </div>
          </div>
          <!-- Carousel End -->
    test_field: 'Test Field'
  -
    id: lf810m8s
    template: |-
      <!-- Banner Start -->
          <div class="container-fluid banner mb-5">
              <div class="container">
                  <div class="row gx-0">
                      <div class="col-lg-4 wow zoomIn" data-wow-delay="0.1s">
                          <div class="bg-primary d-flex flex-column p-5" style="height: 300px;">
                              <h3 class="text-white mb-3">{{opening_hours:title}}</h3>
                              
                              {{opening_hours:opening_hours}}
                              <div class="d-flex justify-content-between text-white mb-3">
                                  <h6 class="text-white mb-0">{{text_1}}</h6>
                                  <p class="mb-0">{{text_2}}</p>
                              </div>
                             {{/opening_hours:opening_hours}}
                              <a class="btn btn-light" href="{{opening_hours:button_link}}">{{opening_hours:link_text}}</a>
                          </div>
                      </div>
                      <div class="col-lg-4 wow zoomIn" data-wow-delay="0.3s">
                          <div class="bg-dark d-flex flex-column p-5" style="height: 300px;">
      	                    
      	                    {{search_a_doctor:search_a_doctor}}
      	                    
      	                    
      	                    
                              
                          </div>
                      </div>
                      <div class="col-lg-4 wow zoomIn" data-wow-delay="0.6s">
                          <div class="bg-secondary d-flex flex-column p-5" style="height: 300px;">
                              <h3 class="text-white mb-3">{{make_appointment_box:title_1}}</h3>
                              <p class="text-white">{{make_appointment_box:title_2}}</p>
                              <h2 class="text-white mb-0">{{make_appointment_box:title_3}}</h2>
                          </div>
                      </div>
                  </div>
              </div>
          </div>
          <!-- Banner Start -->
    type: three_boxes
    enabled: true
  -
    id: lf8038yf
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
    image: about.jpg
  -
    id: lf81m3wi
    title_1: 'We Are A Certified and Award Winning Dental Clinic You Can Trust'
    description: 'Eirmod sed tempor lorem ut dolores. Aliquyam sit sadipscing kasd ipsum. Dolor ea et dolore et at sea ea at dolor, justo ipsum duo rebum sea invidunt voluptua. Eos vero eos vero ea et dolore eirmod et. Dolores diam duo invidunt lorem. Elitr ut dolores magna sit. Sea dolore sanctus sed et. Takimata takimata sanctus sed.'
    appointment_form: |-
      <h1 class="text-white mb-4">Make Appointment</h1>
                              <form>
                                  <div class="row g-3">
                                      <div class="col-12 col-sm-6">
                                          <select class="form-select bg-light border-0" style="height: 55px;">
                                              <option selected>Select A Service</option>
                                              <option value="1">Service 1</option>
                                              <option value="2">Service 2</option>
                                              <option value="3">Service 3</option>
                                          </select>
                                      </div>
                                      <div class="col-12 col-sm-6">
                                          <select class="form-select bg-light border-0" style="height: 55px;">
                                              <option selected>Select Doctor</option>
                                              <option value="1">Doctor 1</option>
                                              <option value="2">Doctor 2</option>
                                              <option value="3">Doctor 3</option>
                                          </select>
                                      </div>
                                      <div class="col-12 col-sm-6">
                                          <input type="text" class="form-control bg-light border-0" placeholder="Your Name" style="height: 55px;">
                                      </div>
                                      <div class="col-12 col-sm-6">
                                          <input type="email" class="form-control bg-light border-0" placeholder="Your Email" style="height: 55px;">
                                      </div>
                                      <div class="col-12 col-sm-6">
                                          <div class="date" id="date1" data-target-input="nearest">
                                              <input type="text"
                                                  class="form-control bg-light border-0 datetimepicker-input"
                                                  placeholder="Appointment Date" data-target="#date1" data-toggle="datetimepicker" style="height: 55px;">
                                          </div>
                                      </div>
                                      <div class="col-12 col-sm-6">
                                          <div class="time" id="time1" data-target-input="nearest">
                                              <input type="text"
                                                  class="form-control bg-light border-0 datetimepicker-input"
                                                  placeholder="Appointment Time" data-target="#time1" data-toggle="datetimepicker" style="height: 55px;">
                                          </div>
                                      </div>
                                      <div class="col-12">
                                          <button class="btn btn-dark w-100 py-3" type="submit">Make Appointment</button>
                                      </div>
                                  </div>
                              </form>
    template: |-
      <!-- Appointment Start -->
          <div class="container-fluid bg-primary bg-appointment my-5 wow fadeInUp" data-wow-delay="0.1s">
              <div class="container">
                  <div class="row gx-5">
                      <div class="col-lg-6 py-5">
                          <div class="py-5">
                              <h1 class="display-5 text-white mb-4">We Are A Certified and Award Winning Dental Clinic You Can Trust</h1>
                              <p class="text-white mb-0">Eirmod sed tempor lorem ut dolores. Aliquyam sit sadipscing kasd ipsum. Dolor ea et dolore et at sea ea at dolor, justo ipsum duo rebum sea invidunt voluptua. Eos vero eos vero ea et dolore eirmod et. Dolores diam duo invidunt lorem. Elitr ut dolores magna sit. Sea dolore sanctus sed et. Takimata takimata sanctus sed.</p>
                          </div>
                      </div>
                      <div class="col-lg-6">
                          <div class="appointment-form h-100 d-flex flex-column justify-content-center text-center p-5 wow zoomIn" data-wow-delay="0.6s">
                             {{appointment_form}}
                          </div>
                      </div>
                  </div>
              </div>
          </div>
          <!-- Appointment End -->
    type: make_appointment_block
    enabled: true
  -
    id: lf81t4ta
    image_before: before.jpg
    image_after: after.jpg
    title_1: 'Our Services'
    title_2: 'We Offer The Best Quality Dental Services'
    services:
      -
        id: lf81ts2f
        title: 'Cosmetic Dentistry'
        image: service-1.jpg
      -
        id: lf81uf61
        title: 'Cosmetic Dentistry'
        image: service-2.jpg
      -
        id: lf81unu8
        title: 'Cosmetic Dentistry'
        image: service-3.jpg
      -
        id: lf81utxm
        title: 'Cosmetic Dentistry'
        image: service-4.jpg
    type: our_services
    enabled: true
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
  -
    id: lf8atsxl
    background_image: carousel-1.jpg
    title: 'Save 30% On Your First Dental Checkup'
    description: 'Eirmod sed tempor lorem ut dolores sit kasd ipsum. Dolor ea et dolore et at sea ea at dolor justo ipsum duo rebum sea. Eos vero eos vero ea et dolore eirmod diam duo lorem magna sit dolore sed et.'
    button_one_link: 'entry::e10495c5-6eca-433b-86a3-bd11c091eb54'
    button_one_link_text: Appointment
    button_two_link: 'entry::62c41548-3890-4058-a6a0-6bf00950f98b'
    button_two_link_text: 'Read More'
    template: |-
      <!-- Offer Start -->
          <div class="container-fluid bg-offer my-5 py-5 wow fadeInUp" style="background:url({{background_image}})" data-wow-delay="0.1s">
              <div class="container py-5">
                  <div class="row justify-content-center">
                      <div class="col-lg-7 wow zoomIn" data-wow-delay="0.6s">
                          <div class="offer-text text-center rounded p-5">
                              <h1 class="display-5 text-white">{{title}}</h1>
                              <p class="text-white mb-4">{{description}}</p>
                              <a href="{{button_one_link}}" class="btn btn-dark py-3 px-5 me-3">{{button_one_link_text}}</a>
                              <a href="{{button_two_link}}" class="btn btn-light py-3 px-5">{{button_two_link_text}}</a>
                          </div>
                      </div>
                  </div>
              </div>
          </div>
    type: offer_highlight
    enabled: true
  -
    id: lf8bqah9
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
  -
    id: lf8c57xj
    background_image: carousel-2.jpg
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
    id: lf97k61q
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
updated_by: e015e865-99ad-436e-af23-ba95eb068b1f
updated_at: 1678856091
---
## Welcome to your brand new Statamic site!

Not sure where to do next? Here are a few ideas, but feel free to explore in your own way, in your own time.

- [Jump into the Control Panel](/cp) and edit this page or begin setting up your own collections and blueprints.
- [Head to the docs](https://statamic.dev) and learn how Statamic works.
- [Watch some Statamic videos](https://youtube.com/statamic) on YouTube.
- [Join our Discord chat](https://statamic.com/discord) and meet thousands of other Statamic developers.
- [Start a discussion](https://github.com/statamic/cms/discussions) and get answers to your questions.
- [Star Statamic on Github](https://github.com/statamic/cms) if you enjoy using it!