<!-- This bit has to be html to achieve the 3 column layout -->
<div class="row row-gap-medium">
  <div class="col-sm-4">
    {% capture the_include %}{% include homepage-key-feature-1.md %}{% endcapture %}
    {{ the_include | markdownify }}
  </div>
  <div class="col-sm-4">
    {% capture the_include %}{% include homepage-key-feature-2.md %}{% endcapture %}
    {{ the_include | markdownify }}
  </div>
  <div class="col-sm-4">
    {% capture the_include %}{% include homepage-key-feature-3.md %}{% endcapture %}
    {{ the_include | markdownify }}
  </div>
</div>
<!-- cloud providers -->
<div class="row row-gap-medium">
  <div class="col-sm-4">
    <p>
      <img src="images/aws.png" style="display: block; margin-left: auto; margin-right: auto; border:0px"/>
    </p>
  </div>
  <div class="col-sm-4">
    <p>
      <img src="images/gcp.png" style="display: block; margin-left: auto; margin-right: auto; border:0px"/>
    </p>
  </div>
  <div class="col-sm-4">
    <p>
      <img src="images/cloudfoundry.png" style="display: block; margin-left: auto; margin-top:85px; margin-right: auto; border:0px"/>
    </p>
  </div>
</div>

---

{% include homepage-getting-started.md %}