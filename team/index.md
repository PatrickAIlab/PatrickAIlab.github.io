---
title: Team
redirect_from:
  - /lab-members
  - /alums
  - /mascots
  - /staff
  - /trainees
---

# <i class="fas fa-users"></i>Team

Our diverse team is composed of a highly enthusiastic and collaborative researchers. We foster a friendly and collaborative environment, where team mmbers can learn from each other.

{% capture html %}
{% include team-list.html role="pi" group="" %}
{% include team-list.html role="postdoc" group="" %}
{% include team-list.html role="phd" group="" %}
{% include team-list.html role="masters" group="" %}
{% include team-list.html role="pharmd" group="" %}
{% include team-list.html role="undergrad" group="" %}
{% include team-list.html role="highschool" group="" %}
{% include team-list.html role="programmer" group="" %}
{% include team-list.html role="mascot" group="" %}
{% endcapture %}

{% include centerer.html html=html %}

<!-- section break -->

## Affiliated members

{% include team-list.html role="affiliate" group="" %}

<!-- section break -->

We are actively recruiting highly motivated graduate students and postdocs with a capable computational background. The Mangul Lab is committed to ensuring an inclusive and supportive environment regardless of age, gender, sexual orientation, disability, race, ethnicity, religion, nationality, or socioeconomic background.

{%
  include big-link.html
  icon="fas fa-hands-helping"
  text="Join the Team"
  link="join"
%}{:.center}

<!-- section break -->

{%
  include figure.html
  image="images/team/group.jpg"
  caption="AI Design Lab Research Group"
  width="100%" 
%}
