---
layout: post
slug: hr example
---

Lorem ipsum[^1] dolor sit amet, consectetur adipiscing elit. Pellentesque vel lacinia neque. Praesent nulla quam, ullamcorper in sollicitudin ac, molestie sed justo. Cras aliquam, sapien id consectetur accumsan, augue magna faucibus ex, ut ultricies turpis tortor vel ante. In at rutrum tellus. Nullam vestibulum metus eu purus malesuada, volutpat mattis leo facilisis. Sed consectetur, nisl et semper laoreet, velit augue congue nunc, eget eleifend odio erat eu sapien. Phasellus dictum efficitur dapibus. Morbi porta lacinia tincidunt. Nam aliquet est mi, nec lacinia ipsum elementum sed. Nam feugiat ipsum tortor, et pretium purus sollicitudin et.

---

<button type="button" class="collapsible">Open Section 3</button>
<div class="content">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}
</script>
  
  ---

Mauris viverra dictum ultricies[^2]. Vestibulum[^3] quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Nunc a egestas tortor, sed feugiat leo. Vestibulum porta tincidunt tellus, vitae ornare tortor. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Sed nunc neque, tempor in iaculis non, faucibus et metus. Etiam id nisl ut lorem gravida euismod.

Fusce non velit cursus ligula mattis convallis vel at metus. Sed pharetra tellus massa, non elementum eros vulputate non. Suspendisse potenti. Quisque arcu felis, laoreet vel accumsan sit amet, fermentum at nunc. Sed massa quam, auctor in eros quis, porttitor tincidunt orci. Nulla convallis id sapien ornare viverra. Cras nec est lacinia ligula porta tincidunt. Nam a est eget ligula pellentesque posuere. Maecenas quis enim ac risus accumsan scelerisque. Aliquam vitae libero sapien. Etiam convallis, metus nec suscipit condimentum, quam massa congue velit, sit amet sollicitudin nisi tortor a lectus. Cras a arcu enim. Suspendisse hendrerit euismod est ac gravida. Donec vitae elit tristique, suscipit eros at, aliquam augue. In ac faucibus dui. Sed tempor lacus tristique elit sagittis, vitae tempor massa convallis.

---
{: data-content="discussions"}

This article has been discussed here:
- [lobste.rs](#)
- [/r/webdev](#)

Feel free to reach out at my email to leave feedback and talk about the article.

---
{: data-content="footnotes"}

[^1]: Okay here I should put something about "ipsum".
[^2]: same goes for this.
[^3]: I studied latin in high school but im not able to translate *anything*! By the way this is a longer footnote and i think it is still pretty cool, even prettier than shortier ones even though it does not say anything useful but whatever.
