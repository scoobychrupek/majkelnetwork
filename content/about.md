+++
title = "O mnie"
template = "about.html"
+++
<div class="about">
<img src="/images/santa-hat.png" class="santa-hat">
<img src="/images/pfp-creep.jpg" class="pfp">
    <div class="about-text">
        <p>Joł to majkel, twórca stronki, na której siedzisz niżej znajdziesz kilka faktów o mnie.</p>
        <p>Moje zajawki - retro, technologia, stare gry, muzyka, gwint, szachy, czytanie.</p>
        <p>Cel - pozostać niezależny.</p>
        <p>Ulubiona gra - Wiedźmin.</p>
        <p>Ulubiony film - trylogia Władcy Pierścieni.</p>
        <p>Ulubione książki - Ted Bundy. Bestia obok mnie, Wiedźmin.</p>
        <p>Przeglądarka - Mozilla Firefox.</p>
    </div>
</div>

<script>
  const today = new Date();
  const month = today.getMonth(); // 0 = styczeń, 11 = grudzień
  const day = today.getDate();

  if (month === 11 && day >= 1 && day <= 31) {
    document.querySelector(".santa-hat").style.display = "block";
  }
</script>

