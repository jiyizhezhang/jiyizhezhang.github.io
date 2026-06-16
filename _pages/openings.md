---
title: "Zhang Group - Openings"
layout: textlay
excerpt: "Vacancies"
sitemap: false
permalink: /vacancies/
---

### Open positions

We are always looking for passionate individuals to join our team! Our job openings will be listed here, also are advertised on the [website](https://www.ce.manchester.ac.uk/study/postgraduate-research/projects/).
We also welcome visiting academic and students for collaborative research.

<br>

#### Current open positions

We don't have open positions at the moment, but stay tuned for future updates! If you find our research interesting, please do reach out. 

<br>



[//]: # (#### Past open positions)

[//]: # ()
[//]: # (Past openings are here:)

[//]: # ()
[//]: # (<br>)



#### PhD and Postdoc scholarship/fellowships
If you are interested in working with us as a PhD student or a postdoc, please send me an email at **jiyizhe.zhang@manchester.ac.uk**. 
Please attach your CV and a brief statement of your motivation, please use the email title "PhD/Postdoc Inquiry-Your Name".

Here are some scholarship opportunities for PhD applicants (for 2026 Fall entry):

- [President's Doctoral Scholarship](https://www.se.manchester.ac.uk/study/postgraduate-research/fees-and-funding/search-for-funding/presidents-doctoral-scholarship/)

- [Dean's Doctoral Scholarship](https://www.se.manchester.ac.uk/study/postgraduate-research/fees-and-funding/search-for-funding/deans-doctoral-scholarship/)

- [CSC joint scholarship](https://www.se.manchester.ac.uk/study/postgraduate-research/fees-and-funding/search-for-funding/china-scholarship-council-joint-scholarship/)

- [Dual-award PhD Program](https://www.manchester.ac.uk/study/postgraduate-research/golden/)


Here are some fellowship opportunities for Postdoc applicants that are highly relevant to our research:

- [Marie Skłodowska-Curie Actions (MSCA) Postdoctoral Fellowships](https://marie-sklodowska-curie-actions.ec.europa.eu/actions/postdoctoral-fellowships)

- [Leverhulme Trust Early Career Fellowships](https://www.leverhulme.ac.uk/early-career-fellowships)

- [Royal Society Newton International Fellowship](https://royalsociety.org/grants/newton-international/)

<br>


#### Master/Undergraduate projects
If you are looking for a MEng/MSc project, please contact me via email or stop by my office (MECD Floor 4 - Office 27) if you are in UoM.



<br>

#### Group activities

<div class="activity-slider" id="group-activity-slider" markdown="0">
<div class="activity-slides">
<div class="activity-slide active"><img src="/images/4_activities/202608-summer_intern1.jpeg" alt="Group activity 1"></div>
<div class="activity-slide"><img src="/images/4_activities/202608-summer_intern2.jpeg" alt="Group activity 2"></div>
</div>
<button class="activity-prev" aria-label="Previous image">&#10094;</button>
<button class="activity-next" aria-label="Next image">&#10095;</button>
<div class="activity-dots">
<button class="activity-dot active" aria-label="Show image 1"></button>
<button class="activity-dot" aria-label="Show image 2"></button>
</div>
</div>

<style>
.activity-slider {
  position: relative;
  width: 100%;
  max-width: 650px;
  margin: 25px auto 10px auto;
  overflow: hidden;
  border-radius: 10px;
}

.activity-slide {
  display: none;
  position: relative;
}

.activity-slide.active {
  display: block;
}

.activity-slide img {
  width: 100%;
  height: 430px;
  object-fit: cover;
  display: block;
  border-radius: 10px;
}

.activity-caption {
  position: absolute;
  left: 0;
  bottom: 0;
  width: 100%;
  padding: 12px 18px;
  background: rgba(0, 0, 0, 0.45);
  color: white;
  font-size: 0.95em;
  box-sizing: border-box;
}

.activity-prev,
.activity-next {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  border: none;
  background: rgba(0, 0, 0, 0.35);
  color: white;
  font-size: 26px;
  padding: 10px 14px;
  cursor: pointer;
  border-radius: 4px;
}

.activity-prev {
  left: 12px;
}

.activity-next {
  right: 12px;
}

.activity-prev:hover,
.activity-next:hover {
  background: rgba(0, 0, 0, 0.6);
}

.activity-dots {
  text-align: center;
  margin-top: 12px;
}

.activity-dot {
  width: 11px;
  height: 11px;
  margin: 0 4px;
  border: none;
  border-radius: 50%;
  background: #bbb;
  cursor: pointer;
}

.activity-dot.active {
  background: #555;
}

@media screen and (max-width: 700px) {
  .activity-slide img {
    height: 260px;
  }
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const slider = document.getElementById("group-activity-slider");
  const slides = slider.querySelectorAll(".activity-slide");
  const dots = slider.querySelectorAll(".activity-dot");
  const prev = slider.querySelector(".activity-prev");
  const next = slider.querySelector(".activity-next");

  let currentSlide = 0;

  function showSlide(index) {
    slides[currentSlide].classList.remove("active");
    dots[currentSlide].classList.remove("active");

    currentSlide = (index + slides.length) % slides.length;

    slides[currentSlide].classList.add("active");
    dots[currentSlide].classList.add("active");
  }

  prev.addEventListener("click", function () {
    showSlide(currentSlide - 1);
  });

  next.addEventListener("click", function () {
    showSlide(currentSlide + 1);
  });

  dots.forEach(function (dot, index) {
    dot.addEventListener("click", function () {
      showSlide(index);
    });
  });
});
</script>