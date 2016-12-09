---
layout: agl
title: Agile Government Handbook
---

{% assign ordered_sections = site.sections | sort: 'order' %}

{% for section in ordered_sections %}

  <div class="fusion-fullwidth fullwidth-box fusion-fullwidth-7  fusion-parallax-none nonhundred-percent-fullwidth" style="border-color:#eae9e9;border-bottom-width: 0px;border-top-width: 0px;border-bottom-style: solid;border-top-style: solid;padding-bottom:80px;padding-top:60px;padding-left:0px;padding-right:0px;background-color:rgba(255,255,255,0);">
    <style type="text/css" scoped="scoped">
      .fusion-fullwidth-7 {
        padding-left: 0px !important;
        padding-right: 0px !important;
      }
    </style>

    <div class="fusion-row">
      <div class="fusion-one-full fusion-layout-column fusion-column-last fusion-spacing-yes" style="margin-top:0px;margin-bottom:20px;">
        <div class="fusion-column-wrapper">
          <div class="fusion-title title fusion-sep-none fusion-title-size-two" style="margin-top:0px;margin-bottom:31px;">
            <h2 class="title-heading-left" id="{{section.title|slugify}}">{{section.title}}</h2></div>
            {{section.content}}
          <div class="fusion-clearfix"></div>
        </div>
      </div>
      <div class="fusion-clearfix"></div>
      <div class="fusion-clearfix"></div>

    </div>
  </div>

{% endfor %}
