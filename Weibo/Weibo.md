![Weibo](https://cdn.jsdelivr.net/gh/DejavuMoe/js@v0.2/img/apps-emoji-7.png)

> 对于Valine评论系统的[自定义表情](https://valine.js.org/emoji.html)和Waline评论系统的[自定义表情](https://waline.js.org/client/emoji.html)，它们的配置类似：

```yaml
    // 这里设置CDN, 默认微博表情CDN
    emojiCDN: 'https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/', 
    // 表情title和图片映射
    emojiMaps: {
"Weibo1": "Weibo/d_aini.webp",
"Weibo2": "Weibo/d_aoteman.webp",
"Weibo3": "Weibo/d_awsl.webp",
"Weibo4": "Weibo/d_baibai.webp",
"Weibo5": "Weibo/d_baobao.webp",
"Weibo6": "Weibo/d_beishang.webp",
"Weibo7": "Weibo/d_bingbujiandan.webp",
"Weibo8": "Weibo/d_bishi.webp",
"Weibo9": "Weibo/d_bizui.webp",
"Weibo10": "Weibo/d_chanzui.webp",
"Weibo11": "Weibo/d_chigua.webp",
"Weibo12": "Weibo/d_chijing.webp",
"Weibo13": "Weibo/d_dacall.webp",
"Weibo14": "Weibo/d_dahaqi.webp",
"Weibo15": "Weibo/d_dalian.webp",
"Weibo16": "Weibo/d_ding.webp",
"Weibo17": "Weibo/d_doge.webp",
"Weibo18": "Weibo/d_erha.webp",
"Weibo19": "Weibo/d_feijie.webp",
"Weibo20": "Weibo/d_feizao.webp",
"Weibo21": "Weibo/d_ganmao.webp",
"Weibo22": "Weibo/d_guile.webp",
"Weibo23": "Weibo/d_guzhang.webp",
"Weibo24": "Weibo/d_haha.webp",
"Weibo25": "Weibo/d_haixiu.webp",
"Weibo26": "Weibo/d_han.webp",
"Weibo27": "Weibo/d_hehe.webp",
"Weibo28": "Weibo/d_heiheihei.webp",
"Weibo29": "Weibo/d_heixian.webp",
"Weibo30": "Weibo/d_heng.webp",
"Weibo31": "Weibo/d_huaixiao.webp",
"Weibo32": "Weibo/d_huaxin.webp",
"Weibo33": "Weibo/d_jiyan.webp",
"Weibo34": "Weibo/d_keai.webp",
"Weibo35": "Weibo/d_kele.webp",
"Weibo36": "Weibo/d_kelian.webp",
"Weibo37": "Weibo/d_ku.webp",
"Weibo38": "Weibo/d_kulou.webp",
"Weibo39": "Weibo/d_kun.webp",
"Weibo40": "Weibo/d_landelini.webp",
"Weibo41": "Weibo/d_lang.webp",
"Weibo42": "Weibo/d_lei.webp",
"Weibo43": "Weibo/d_miao.webp",
"Weibo44": "Weibo/d_nanhaier.webp",
"Weibo45": "Weibo/d_nu.webp",
"Weibo46": "Weibo/d_numa.webp",
"Weibo47": "Weibo/d_nvhaier.webp",
"Weibo48": "Weibo/d_qian.webp",
"Weibo49": "Weibo/d_qinqin.webp",
"Weibo50": "Weibo/d_qiurao.webp",
"Weibo51": "Weibo/d_shayan.webp",
"Weibo52": "Weibo/d_shengbing.webp",
"Weibo53": "Weibo/d_shenshou.webp",
"Weibo54": "Weibo/d_shiwang.webp",
"Weibo55": "Weibo/d_shuai.webp",
"Weibo56": "Weibo/d_shuijiao.webp",
"Weibo57": "Weibo/d_sikao.webp",
"Weibo58": "Weibo/d_suan.webp",
"Weibo59": "Weibo/d_taikaixin.webp",
"Weibo60": "Weibo/d_tanshou.webp",
"Weibo61": "Weibo/d_tian.webp",
"Weibo62": "Weibo/d_touxiao.webp",
"Weibo63": "Weibo/d_tu.webp",
"Weibo64": "Weibo/d_tuzi.webp",
"Weibo65": "Weibo/d_wabishi.webp",
"Weibo66": "Weibo/d_weiqu.webp",
"Weibo67": "Weibo/d_wu.webp",
"Weibo68": "Weibo/d_xiaoku.webp",
"Weibo69": "Weibo/d_xingxingyan.webp",
"Weibo70": "Weibo/d_xiongmao.webp",
"Weibo71": "Weibo/d_xixi.webp",
"Weibo72": "Weibo/d_xu.webp",
"Weibo73": "Weibo/d_yinxian.webp",
"Weibo74": "Weibo/d_yiwen.webp",
"Weibo75": "Weibo/d_youhengheng.webp",
"Weibo76": "Weibo/d_yun.webp",
"Weibo77": "Weibo/d_yunbei.webp",
"Weibo78": "Weibo/d_zhuakuang.webp",
"Weibo79": "Weibo/d_zhutou.webp",
"Weibo80": "Weibo/d_zuohengheng.webp",
"Weibo81": "Weibo/emoji_0x1f44f.webp",
"Weibo82": "Weibo/emoji_0x1f47b.webp",
"Weibo83": "Weibo/emoji_0x1f4a3.webp",
"Weibo84": "Weibo/f_geili.webp",
"Weibo85": "Weibo/f_hufen.webp",
"Weibo86": "Weibo/h_buyao.webp",
"Weibo87": "Weibo/h_good.webp",
"Weibo88": "Weibo/h_haha.webp",
"Weibo89": "Weibo/h_jiayou.webp",
"Weibo90": "Weibo/h_lai.webp",
"Weibo91": "Weibo/h_ok.webp",
"Weibo92": "Weibo/h_quantou.webp",
"Weibo93": "Weibo/h_ruo.webp",
"Weibo94": "Weibo/h_woshou.webp",
"Weibo95": "Weibo/h_ye.webp",
"Weibo96": "Weibo/h_zan.webp",
"Weibo97": "Weibo/h_zuoyi.webp",
"Weibo98": "Weibo/l_shangxin.webp",
"Weibo99": "Weibo/l_xin.webp",
}
```

> 对于其他评论系统可用的Markdown格式图片链接：

```markdown
![Weibo1](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_aini.webp)
![Weibo2](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_aoteman.webp)
![Weibo3](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_awsl.webp)
![Weibo4](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_baibai.webp)
![Weibo5](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_baobao.webp)
![Weibo6](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_beishang.webp)
![Weibo7](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_bingbujiandan.webp)
![Weibo8](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_bishi.webp)
![Weibo9](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_bizui.webp)
![Weibo10](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_chanzui.webp)
![Weibo11](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_chigua.webp)
![Weibo12](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_chijing.webp)
![Weibo13](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_dacall.webp)
![Weibo14](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_dahaqi.webp)
![Weibo15](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_dalian.webp)
![Weibo16](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_ding.webp)
![Weibo17](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_doge.webp)
![Weibo18](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_erha.webp)
![Weibo19](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_feijie.webp)
![Weibo20](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_feizao.webp)
![Weibo21](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_ganmao.webp)
![Weibo22](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_guile.webp)
![Weibo23](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_guzhang.webp)
![Weibo24](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_haha.webp)
![Weibo25](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_haixiu.webp)
![Weibo26](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_han.webp)
![Weibo27](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_hehe.webp)
![Weibo28](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_heiheihei.webp)
![Weibo29](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_heixian.webp)
![Weibo30](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_heng.webp)
![Weibo31](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_huaixiao.webp)
![Weibo32](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_huaxin.webp)
![Weibo33](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_jiyan.webp)
![Weibo34](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_keai.webp)
![Weibo35](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_kele.webp)
![Weibo36](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_kelian.webp)
![Weibo37](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_ku.webp)
![Weibo38](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_kulou.webp)
![Weibo39](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_kun.webp)
![Weibo40](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_landelini.webp)
![Weibo41](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_lang.webp)
![Weibo42](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_lei.webp)
![Weibo43](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_miao.webp)
![Weibo44](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_nanhaier.webp)
![Weibo45](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_nu.webp)
![Weibo46](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_numa.webp)
![Weibo47](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_nvhaier.webp)
![Weibo48](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_qian.webp)
![Weibo49](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_qinqin.webp)
![Weibo50](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_qiurao.webp)
![Weibo51](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_shayan.webp)
![Weibo52](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_shengbing.webp)
![Weibo53](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_shenshou.webp)
![Weibo54](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_shiwang.webp)
![Weibo55](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_shuai.webp)
![Weibo56](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_shuijiao.webp)
![Weibo57](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_sikao.webp)
![Weibo58](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_suan.webp)
![Weibo59](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_taikaixin.webp)
![Weibo60](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_tanshou.webp)
![Weibo61](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_tian.webp)
![Weibo62](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_touxiao.webp)
![Weibo63](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_tu.webp)
![Weibo64](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_tuzi.webp)
![Weibo65](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_wabishi.webp)
![Weibo66](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_weiqu.webp)
![Weibo67](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_wu.webp)
![Weibo68](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_xiaoku.webp)
![Weibo69](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_xingxingyan.webp)
![Weibo70](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_xiongmao.webp)
![Weibo71](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_xixi.webp)
![Weibo72](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_xu.webp)
![Weibo73](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_yinxian.webp)
![Weibo74](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_yiwen.webp)
![Weibo75](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_youhengheng.webp)
![Weibo76](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_yun.webp)
![Weibo77](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_yunbei.webp)
![Weibo78](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_zhuakuang.webp)
![Weibo79](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_zhutou.webp)
![Weibo80](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/d_zuohengheng.webp)
![Weibo81](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/emoji_0x1f44f.webp)
![Weibo82](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/emoji_0x1f47b.webp)
![Weibo83](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/emoji_0x1f4a3.webp)
![Weibo84](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/f_geili.webp)
![Weibo85](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/f_hufen.webp)
![Weibo86](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/h_buyao.webp)
![Weibo87](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/h_good.webp)
![Weibo88](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/h_haha.webp)
![Weibo89](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/h_jiayou.webp)
![Weibo90](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/h_lai.webp)
![Weibo91](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/h_ok.webp)
![Weibo92](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/h_quantou.webp)
![Weibo93](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/h_ruo.webp)
![Weibo94](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/h_woshou.webp)
![Weibo95](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/h_ye.webp)
![Weibo96](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/h_zan.webp)
![Weibo97](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/h_zuoyi.webp)
![Weibo98](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/l_shangxin.webp)
![Weibo99](https://cdn.jsdelivr.net/gh/DejavuMoe/BQB@v1.0.0/Weibo/l_xin.webp)
```