---
id: aff18efc-b85a-4d79-af14-92bebf5a76ef
blueprint: page
title: Contact
author: e015e865-99ad-436e-af23-ba95eb068b1f
updated_by: e015e865-99ad-436e-af23-ba95eb068b1f
updated_at: 1678857796
block_types:
  -
    id: lf98it4x
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
    id: lf98ix4z
    title: 'Contact Us'
    sub_title: 'Feel Free To Contact Us'
    line_items:
      -
        id: lf98iz89
        icon: bi-geo-alt
        text_1: 'Our Office'
        text_2: '123 Street, New York, USA'
      -
        id: lf98j2oo
        icon: bi-envelope-open
        text_1: 'Email Us'
        text_2: info@example.com
      -
        id: lf98ji3c
        icon: bi-phone-vibrate
        text_1: 'Call Us'
        text_2: '+918907289865'
    google_map_iframe: |-
      <iframe class="position-relative rounded w-100 h-100"
                              src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3001156.4288297426!2d-78.01371936852176!3d42.72876761954724!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4ccc4bf0f123a5a9%3A0xddcfc6c1de189567!2sNew%20York%2C%20USA!5e0!3m2!1sen!2sbd!4v1603794290143!5m2!1sen!2sbd"
                              frameborder="0" style="min-height: 400px; border:0;" allowfullscreen="" aria-hidden="false"
                              tabindex="0"></iframe>
    template: |-
      <!-- Contact Start -->
          <div class="container-fluid py-5">
              <div class="container">
                  <div class="row g-5">
                      <div class="col-xl-4 col-lg-6 wow slideInUp" data-wow-delay="0.1s">
                          <div class="bg-light rounded h-100 p-5">
                              <div class="section-title">
                                  <h5 class="position-relative d-inline-block text-primary text-uppercase">{{title}}</h5>
                                  <h1 class="display-6 mb-4">{{sub_title}}</h1>
                              </div>
                              
                              
                              {{line_items}}
                              
                              <div class="d-flex align-items-center mb-2">
                                  <i class="bi {{icon}} fs-1 text-primary me-3"></i>
                                  <div class="text-start">
                                      <h5 class="mb-0">{{text_1}}</h5>
                                      <span>{{text_2}}</span>
                                  </div>
                              </div>
                              
                              {{/line_items}}
                              
                              
                          </div>
                      </div>
                      <div class="col-xl-4 col-lg-6 wow slideInUp" data-wow-delay="0.3s">
                          <form>
                              <div class="row g-3">
                                  <div class="col-12">
                                      <input type="text" class="form-control border-0 bg-light px-4" placeholder="Your Name" style="height: 55px;">
                                  </div>
                                  <div class="col-12">
                                      <input type="email" class="form-control border-0 bg-light px-4" placeholder="Your Email" style="height: 55px;">
                                  </div>
                                  <div class="col-12">
                                      <input type="text" class="form-control border-0 bg-light px-4" placeholder="Subject" style="height: 55px;">
                                  </div>
                                  <div class="col-12">
                                      <textarea class="form-control border-0 bg-light px-4 py-3" rows="5" placeholder="Message"></textarea>
                                  </div>
                                  <div class="col-12">
                                      <button class="btn btn-primary w-100 py-3" type="submit">Send Message</button>
                                  </div>
                              </div>
                          </form>
                      </div>
                      <div class="col-xl-4 col-lg-12 wow slideInUp" data-wow-delay="0.6s">
                          {{google_map_iframe}}
                      </div>
                  </div>
              </div>
          </div>
          <!-- Contact End -->
    type: contact_us
    enabled: true
template: home
---
