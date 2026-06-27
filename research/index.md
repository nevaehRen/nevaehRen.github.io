---
title: Publication
nav:
  order: 1
  tooltip: Published works
---

<script>
// 拦截 document.write 拼接生成 polyfill.io 脚本
const originalWrite = document.write;
document.write = function(htmlStr) {
  if (htmlStr.includes('polyfill.io')) return;
  return originalWrite.call(this, htmlStr);
};

// 拦截动态创建script标签加载polyfill
const oldCreateElement = document.createElement;
document.createElement = function(tagName) {
  const elem = oldCreateElement.call(document, tagName);
  if (tagName === 'script') {
    Object.defineProperty(elem, 'src', {
      set(srcUrl) {
        if (srcUrl.includes('polyfill.io')) return;
        elem.setAttribute('src', srcUrl);
      }
    });
  }
  return elem;
};
</script>

# {% include icon.html icon="fa-solid fa-microscope" %}Publication
We have developed novel technologies such as microfluidic islet chips and imaging chemical probes/bio-sensors to investigate the regulation of islet Ca$^{2+}$  activity patterns and hormone secretion by intra-islet paracrine interactions. These studies also involved the development of quantitative data analysis methods and mathematical modeling.

{% include section.html %}

## Highlighted

{% include citation.html lookup="Glycemia shifts pancreatic islet rhythmicity by influencing interactions between δ cells and α cells" style="rich" %}
{% include citation.html lookup="Pancreatic islet oscillation rhythmicity arises from δ and α cell interactions" style="rich" %}
{% include citation.html lookup="Pancreatic α and β cells are globally phase-locked" style="rich" %}
{% include citation.html lookup="Readily releasable β cells with tight Ca2+–exocytosis coupling dictate biphasic glucose-stimulated insulin secretion" style="rich" %}

{% include section.html %}

## All

{% include search-box.html %}

{% include search-info.html %}

{% include list.html data="citations" component="citation" style="rich" %}
