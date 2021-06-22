![美团](https://cdn.jsdelivr.net/gh/DejavuMoe/js@v0.2/img/apps-emoji-2.png)

> 对于Valine评论系统的[自定义表情](https://valine.js.org/emoji.html)和Waline评论系统的[自定义表情](https://waline.js.org/client/emoji.html)，它们的配置类似：

```yaml
    // 这里设置CDN, 默认微博表情CDN
    emojiCDN: 'https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/', 
    // 表情title和图片映射
    emojiMaps: {
"Meituan1": "Meituan/0.webp",
"Meituan2": "Meituan/1.webp",
"Meituan3": "Meituan/10.webp",
"Meituan4": "Meituan/100.webp",
"Meituan5": "Meituan/101.webp",
"Meituan6": "Meituan/102.webp",
"Meituan7": "Meituan/11.webp",
"Meituan8": "Meituan/12.webp",
"Meituan9": "Meituan/13.webp",
"Meituan10": "Meituan/14.webp",
"Meituan11": "Meituan/15.webp",
"Meituan12": "Meituan/16.webp",
"Meituan13": "Meituan/17.webp",
"Meituan14": "Meituan/18.webp",
"Meituan15": "Meituan/19.webp",
"Meituan16": "Meituan/2.webp",
"Meituan17": "Meituan/20.webp",
"Meituan18": "Meituan/21.webp",
"Meituan19": "Meituan/22.webp",
"Meituan20": "Meituan/23.webp",
"Meituan21": "Meituan/24.webp",
"Meituan22": "Meituan/25.webp",
"Meituan23": "Meituan/26.webp",
"Meituan24": "Meituan/27.webp",
"Meituan25": "Meituan/28.webp",
"Meituan26": "Meituan/29.webp",
"Meituan27": "Meituan/3.webp",
"Meituan28": "Meituan/30.webp",
"Meituan29": "Meituan/31.webp",
"Meituan30": "Meituan/32.webp",
"Meituan31": "Meituan/33.webp",
"Meituan32": "Meituan/34.webp",
"Meituan33": "Meituan/35.webp",
"Meituan34": "Meituan/36.webp",
"Meituan35": "Meituan/37.webp",
"Meituan36": "Meituan/38.webp",
"Meituan37": "Meituan/39.webp",
"Meituan38": "Meituan/4.webp",
"Meituan39": "Meituan/40.webp",
"Meituan40": "Meituan/41.webp",
"Meituan41": "Meituan/42.webp",
"Meituan42": "Meituan/43.webp",
"Meituan43": "Meituan/44.webp",
"Meituan44": "Meituan/45.webp",
"Meituan45": "Meituan/46.webp",
"Meituan46": "Meituan/47.webp",
"Meituan47": "Meituan/48.webp",
"Meituan48": "Meituan/49.webp",
"Meituan49": "Meituan/5.webp",
"Meituan50": "Meituan/50.webp",
"Meituan51": "Meituan/51.webp",
"Meituan52": "Meituan/52.webp",
"Meituan53": "Meituan/53.webp",
"Meituan54": "Meituan/54.webp",
"Meituan55": "Meituan/55.webp",
"Meituan56": "Meituan/56.webp",
"Meituan57": "Meituan/57.webp",
"Meituan58": "Meituan/58.webp",
"Meituan59": "Meituan/59.webp",
"Meituan60": "Meituan/6.webp",
"Meituan61": "Meituan/60.webp",
"Meituan62": "Meituan/61.webp",
"Meituan63": "Meituan/62.webp",
"Meituan64": "Meituan/63.webp",
"Meituan65": "Meituan/64.webp",
"Meituan66": "Meituan/65.webp",
"Meituan67": "Meituan/66.webp",
"Meituan68": "Meituan/67.webp",
"Meituan69": "Meituan/68.webp",
"Meituan70": "Meituan/69.webp",
"Meituan71": "Meituan/7.webp",
"Meituan72": "Meituan/70.webp",
"Meituan73": "Meituan/71.webp",
"Meituan74": "Meituan/72.webp",
"Meituan75": "Meituan/73.webp",
"Meituan76": "Meituan/74.webp",
"Meituan77": "Meituan/75.webp",
"Meituan78": "Meituan/76.webp",
"Meituan79": "Meituan/77.webp",
"Meituan80": "Meituan/78.webp",
"Meituan81": "Meituan/79.webp",
"Meituan82": "Meituan/8.webp",
"Meituan83": "Meituan/80.webp",
"Meituan84": "Meituan/81.webp",
"Meituan85": "Meituan/82.webp",
"Meituan86": "Meituan/83.webp",
"Meituan87": "Meituan/84.webp",
"Meituan88": "Meituan/85.webp",
"Meituan89": "Meituan/86.webp",
"Meituan90": "Meituan/87.webp",
"Meituan91": "Meituan/88.webp",
"Meituan92": "Meituan/89.webp",
"Meituan93": "Meituan/9.webp",
"Meituan94": "Meituan/90.webp",
"Meituan95": "Meituan/91.webp",
"Meituan96": "Meituan/92.webp",
"Meituan97": "Meituan/93.webp",
"Meituan98": "Meituan/94.webp",
"Meituan99": "Meituan/95.webp",
"Meituan100": "Meituan/96.webp",
"Meituan101": "Meituan/97.webp",
"Meituan102": "Meituan/98.webp",
"Meituan103": "Meituan/99.webp",
}
```

> 对于其他评论系统可用的Markdown格式图片链接：

```markdown
![Meituan1](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/0.webp)
![Meituan2](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/1.webp)
![Meituan3](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/10.webp)
![Meituan4](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/100.webp)
![Meituan5](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/101.webp)
![Meituan6](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/102.webp)
![Meituan7](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/11.webp)
![Meituan8](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/12.webp)
![Meituan9](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/13.webp)
![Meituan10](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/14.webp)
![Meituan11](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/15.webp)
![Meituan12](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/16.webp)
![Meituan13](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/17.webp)
![Meituan14](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/18.webp)
![Meituan15](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/19.webp)
![Meituan16](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/2.webp)
![Meituan17](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/20.webp)
![Meituan18](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/21.webp)
![Meituan19](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/22.webp)
![Meituan20](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/23.webp)
![Meituan21](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/24.webp)
![Meituan22](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/25.webp)
![Meituan23](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/26.webp)
![Meituan24](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/27.webp)
![Meituan25](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/28.webp)
![Meituan26](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/29.webp)
![Meituan27](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/3.webp)
![Meituan28](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/30.webp)
![Meituan29](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/31.webp)
![Meituan30](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/32.webp)
![Meituan31](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/33.webp)
![Meituan32](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/34.webp)
![Meituan33](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/35.webp)
![Meituan34](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/36.webp)
![Meituan35](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/37.webp)
![Meituan36](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/38.webp)
![Meituan37](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/39.webp)
![Meituan38](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/4.webp)
![Meituan39](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/40.webp)
![Meituan40](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/41.webp)
![Meituan41](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/42.webp)
![Meituan42](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/43.webp)
![Meituan43](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/44.webp)
![Meituan44](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/45.webp)
![Meituan45](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/46.webp)
![Meituan46](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/47.webp)
![Meituan47](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/48.webp)
![Meituan48](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/49.webp)
![Meituan49](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/5.webp)
![Meituan50](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/50.webp)
![Meituan51](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/51.webp)
![Meituan52](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/52.webp)
![Meituan53](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/53.webp)
![Meituan54](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/54.webp)
![Meituan55](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/55.webp)
![Meituan56](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/56.webp)
![Meituan57](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/57.webp)
![Meituan58](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/58.webp)
![Meituan59](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/59.webp)
![Meituan60](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/6.webp)
![Meituan61](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/60.webp)
![Meituan62](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/61.webp)
![Meituan63](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/62.webp)
![Meituan64](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/63.webp)
![Meituan65](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/64.webp)
![Meituan66](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/65.webp)
![Meituan67](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/66.webp)
![Meituan68](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/67.webp)
![Meituan69](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/68.webp)
![Meituan70](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/69.webp)
![Meituan71](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/7.webp)
![Meituan72](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/70.webp)
![Meituan73](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/71.webp)
![Meituan74](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/72.webp)
![Meituan75](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/73.webp)
![Meituan76](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/74.webp)
![Meituan77](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/75.webp)
![Meituan78](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/76.webp)
![Meituan79](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/77.webp)
![Meituan80](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/78.webp)
![Meituan81](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/79.webp)
![Meituan82](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/8.webp)
![Meituan83](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/80.webp)
![Meituan84](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/81.webp)
![Meituan85](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/82.webp)
![Meituan86](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/83.webp)
![Meituan87](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/84.webp)
![Meituan88](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/85.webp)
![Meituan89](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/86.webp)
![Meituan90](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/87.webp)
![Meituan91](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/88.webp)
![Meituan92](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/89.webp)
![Meituan93](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/9.webp)
![Meituan94](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/90.webp)
![Meituan95](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/91.webp)
![Meituan96](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/92.webp)
![Meituan97](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/93.webp)
![Meituan98](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/94.webp)
![Meituan99](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/95.webp)
![Meituan100](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/96.webp)
![Meituan101](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/97.webp)
![Meituan102](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/98.webp)
![Meituan103](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Meituan/99.webp)
```