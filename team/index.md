---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# <i class="fas fa-users"></i>Team

{% include section.html %}

{%
  include list.html
  data="members"
  component="portrait"
  filters="role: pi"
%}

{:.center}

{% include section.html background="images/kabocha.jpg" dark=false%}

{% include section.html %}

## Funding

{:.center}

{%
  include gallery.html
  style="square"

  image1="images/nhaes.png"
  link1="https://colsa.unh.edu/new-hampshire-agricultural-experiment-station"
  tooltip1="NHAES"

%}
