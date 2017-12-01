---
layout: default
---

<div style=""><img style="height:400px;width:600px" src="pictures/潮汐猎人载入.jpeg"></div>

<div style=""><h2>潮汐猎人（简称：潮汐，英文简称：TH，外号：西瓜皮）</h2></div>
<br>

<div style=""><h3>属性（裸装）：</h3><br><br>

    <div>
    <span style="line-height: 18px;">
        等级:<select id="level">
                <option value="1" selected>1级</option>
                <option value="2">2级</option>
                <option value="3">3级</option>
                <option value="4">4级</option>
                <option value="5">5级</option>
                <option value="6">6级</option>
                <option value="7">7级</option>
                <option value="8">8级</option>
                <option value="9">9级</option>
                <option value="10">10级</option>
                <option value="11">11级</option>
                <option value="12">12级</option>
                <option value="13">13级</option>
                <option value="14">14级</option>
                <option value="15">15级</option>
                <option value="16">16级</option>
                <option value="17">17级</option>
                <option value="18">18级</option>
                <option value="19">19级</option>
                <option value="20">20级</option>
                <option value="21">21级</option>
                <option value="22">22级</option>
                <option value="23">23级</option>
                <option value="24">24级</option>
                <option value="25">25级</option>
            </select><br/>
        力量:<span id="str"></span>
        敏捷:<span id="agi"></span>
        智力:<span id="int"></span>
    </span>
    </div>

    <table border="1" cellpadding="3" cellspacing="1" style="width:100%">

        <tbody>

        <tr>
            <td>气血</td>
            <td>魔法</td>
            <td>攻击力</td>
            <td>攻击距离</td>
        </tr>
        
        <tr>
            <td><span id="health"></span></td>
            <td><span id="mana"></span></td>
            <td><span id="attack"></span></td>
            <td><span id="attack_range"></span></td>
        </tr>

        <tr>
            <td>攻速</td>
            <td>移速</td>
            <td>护甲</td>
            <td>魔法抗性</td>
        </tr>
        
        <tr>
            <td><span id="attack_speed"></span></td>
            <td><span id="speed"></span></td>
            <td><span id="armor"></span></td>
            <td><span id="magic_resistance"></span>%</td>
        </tr>

        <tr>
            <td>技能增强</td>
            <td>生命恢复</td>
            <td>魔法恢复</td>
            <td class="state_resistance">状态抗性</td>
        </tr>
        
        <tr>
            <td><span id="magic_increase"></span>%</td>
            <td><span id="health_recover"></span>%</td>
            <td><span id="mana_recover"></span>%</td>
            <td class="state_resistance"><span id="state_resistance"></span>%</td>
        </tr>

        </tbody>
    </table>

</div>

<div><br></div>
<div><br></div>

<div style=""><h3>定位：</h3></div>
<div style="">
    <img style="height:300px;width:300px" src="pictures/潮汐猎人定位.png">
</div>
<div style=""><br></div>
<div style=""><br></div>

<div>
    <div><h3>技能介绍：</h3></div>
    <div>一技能：巨浪<img src="pictures/一技能.jpg"></div>
    <div><br></div>
    <div>
        <img src="pictures/一技能介绍.png">
    </div>
</div>
<div><br></div>
<div>tips：</div>
<div>
    <div>1、该技能可用阿哈利姆神杖升级技能威力。巨浪变成点地施放的波形技能，可以作用于直线上的单位。减少冷却时间。</div>
    <div>神杖升级距离：1800</div>
    <div>神杖升级作用范围：240</div>
    <div>神杖升级冷却时间：7秒</div>
    <div><br></div>
    <!-- <div><img src="pictures/潮汐A帐一技能.gif"></div> -->
    <br>
    <br>
    <div><span style="background-color: rgb(255, 255, 255); color: rgb(51, 51, 51);"><br></span></div>
</div>
<div><font color="#333333">二技能：海妖外壳</font><img src="pictures/二技能.jpg"></div>
<div><br></div>
<div>
    <img src="pictures/二技能介绍.png">
</div>
<div>
    <div>如果6秒内没有受到来自玩家的伤害，伤害累计值将重置。</div>
    <div>海妖外壳能移除绝大多数负面状态，即使该状态效果无法驱散。</div>
</div>
<div><br></div>
<div>tips：</div>
<div>
    1、带有伤害格挡的物品有：圆盾、先锋盾、赤红甲、大晕锤（深渊之刃）。“不与带有伤害格挡的物品叠加”，所以潮汐不推荐出圆盾、先锋盾、赤红甲、大晕锤（深渊之刃）。
</div>
<div>2、海妖外壳伤害达到临界值时能移除像眩晕、沉默等debuff。图中为解除血棘沉默时的效果。</div>
<!-- <div><img src="pictures/海妖外壳解debuff.gif"><br><br></div> -->
<div><br></div>
<div><br></div>
<div>三技能：锚击<img src="pictures/三技能.jpg"></div>
<div><br></div>
<div>
    <img src="pictures/三技能介绍.png">
</div>
<div><br></div>
<div>tips：</div>
<div>1、因为
    “无视技能免疫：是”，所以锚击可以对魔免状态下的单位降低攻击力。&nbsp;<span style="text-indent: 2em;">因为 “伤害类型：物理”
，所以锚击可以对魔免状态下的单位造成伤害。</span><span style="text-indent: 2em;">两个属性组合在一起，所以锚击可以对魔免状态下的单位造成伤害并且降低攻击力。</span></div>
<div>2、“<span style="text-indent: 2em;">伤害类型：物理</span><span style="text-indent: 2em;">”，所以实际造成的伤害计算的是敌方单位的“物理抗性”，敌方护甲越高，锚击造成伤害越低，所以配合一技能巨浪的减甲，效果更佳。</span>
</div>
<div><span style="text-indent: 2em;">3、锚击的减伤 配合
海妖外壳的格挡，可以帮助潮汐“无伤”打野。省去数据收集计算实践分析环节，直接得出以下结论：</span></div>
<div><span style="text-indent: 2em;">1）4级潮汐（2级外壳+2级锚击），只有大撒（萨特苦难行者）、人马（半人马征服者）、大熊怪（地狱熊怪粉碎者）、雕哥（枭兽撕裂者）在被减攻后还能对潮汐造成伤害，其他野怪在减攻后都无法对潮汐造成伤害。</span>
</div>
<div><span style="text-indent: 2em;">2）5级潮汐（2外壳+3锚击 或者
3外壳+2锚击），所有普通野怪在被锚击减伤后，都无法对潮汐造成伤害。</span></div>
<div><span style="text-indent: 2em;">3</span>）远古黑龙的攻击力为64，潮汐得有3级外壳+3级锚击才能无伤。</div>
<div><span style="text-indent: 2em;">4）</span>远古雷肤兽的攻击力为62+9，潮汐得有3级外壳+3级锚击才能无伤。</div>
<div>5）远古花岗石傀儡的攻击力为82，潮汐得4级外壳+3级锚击或者3级外壳+4级锚击才能无伤。</div>
<div>6）远古萨满潜行者。。。潮汐前期看到它就放弃打远古吧。。。</div>
<div><br></div>
<div>四技能：毁灭<img src="pictures/四技能.png"></div>
<div><br></div>
<div>
    <img src="pictures/四技能介绍.png">
</div>
<div><br></div>
<div>tips：</div>
<div>
    1、大秘刷秘大是出了刷新球之后的必备口诀。如果只是大刷大，耗蓝为325+375+325=1025。而使用口诀之后，耗蓝为325-135+375-135+325=755。如果为卫士胫甲的话，耗蓝为<span
        style="text-indent: 2em;">325-160+375-160+325=705。</span></div>
<div><br></div>
<!-- <div><img src="pictures/大秘刷秘大.gif"><br></div> -->
<span style="text-indent: 28px;">如图所示，大刷大的潮汐放完两个大后就空蓝了，使用大秘刷秘大口诀的潮汐结束还有三分之一所有的蓝，还能继续放其他技能。</span>
<div><br></div>
<div><br></div>

<div><h3>天赋：</h3></div>
<div><img src="pictures/天赋.png"></div>
<div><br></div>
<div><br></div>

<div>
    <div><span style="text-indent: 2em;"><h3>技能天赋加点：</h3></span></div>
    <div><span style="text-indent: 2em;">建议一：前期发育很不顺，需要15级点经验天赋帮助自己提升等级</span></div>
    <div><span style="text-indent: 2em;">&nbsp;</span><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOqZFH5d"
            target="_blank"><img src="http://s14.sinaimg.cn/mw690/002jW8tbzy7gbSOqZFH5d&amp;690"
                                 name="image_operate_78741511956851817"></a><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOtz7C9c"
            target="_blank"><img src="http://s13.sinaimg.cn/mw690/002jW8tbzy7gbSOtz7C9c&amp;690"
                                 name="image_operate_14581511956861801"></a><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOtz7C9c"
            target="_blank"><img src="http://s13.sinaimg.cn/mw690/002jW8tbzy7gbSOtz7C9c&amp;690"
                                 name="image_operate_14581511956861801"></a><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOqZFH5d"
            target="_blank"><img src="http://s14.sinaimg.cn/mw690/002jW8tbzy7gbSOqZFH5d&amp;690"
                                 name="image_operate_78741511956851817"></a><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOtz7C9c"
            target="_blank"><img src="http://s13.sinaimg.cn/mw690/002jW8tbzy7gbSOtz7C9c&amp;690"
                                 name="image_operate_14581511956861801"></a><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd2e08ex85"
            target="_blank"><img src="http://s6.sinaimg.cn/mw690/002jW8tbzy7gd2e08ex85&amp;690"
                                 name="image_operate_89361512024875922"></a><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSODSEMa0"
            target="_blank"><img src="http://s1.sinaimg.cn/mw690/002jW8tbzy7gbSODSEMa0&amp;690"
                                 name="image_operate_64011511956853651"></a><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOtz7C9c"
            target="_blank"><img src="http://s13.sinaimg.cn/mw690/002jW8tbzy7gbSOtz7C9c&amp;690"
                                 name="image_operate_14581511956861801"></a><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOqZFH5d"
            target="_blank"><img src="http://s14.sinaimg.cn/mw690/002jW8tbzy7gbSOqZFH5d&amp;690"
                                 name="image_operate_78741511956851817"></a><span style="text-indent: 2em;">左</span><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOqZFH5d"
            target="_blank"><img src="http://s14.sinaimg.cn/mw690/002jW8tbzy7gbSOqZFH5d&amp;690"
                                 name="image_operate_78741511956851817"></a><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd2e08ex85"
            target="_blank"><img src="http://s6.sinaimg.cn/mw690/002jW8tbzy7gd2e08ex85&amp;690"
                                 name="image_operate_74571512024915677"></a><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSODSEMa0"
            target="_blank"><img src="http://s1.sinaimg.cn/mw690/002jW8tbzy7gbSODSEMa0&amp;690"
                                 name="image_operate_64011511956853651"></a><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSODSEMa0"
            target="_blank"><img src="http://s1.sinaimg.cn/mw690/002jW8tbzy7gbSODSEMa0&amp;690"
                                 name="image_operate_64011511956853651"></a><span style="text-indent: 2em;">右</span><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSODSEMa0"
            target="_blank"><img src="http://s1.sinaimg.cn/mw690/002jW8tbzy7gbSODSEMa0&amp;690"
                                 name="image_operate_64011511956853651"></a><a
            href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd2e08ex85"
            target="_blank"><img src="http://s6.sinaimg.cn/mw690/002jW8tbzy7gd2e08ex85&amp;690"
                                 name="image_operate_71091512024911243"></a><span style="text-indent: 2em;">右右</span>
    </div>
    <br></div>
<div><span style="text-indent: 2em;">建议二：对面物理输出英雄多，加大减伤削弱对面输出</span></div>
<div>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOqZFH5d"
        target="_blank"><img src="http://s14.sinaimg.cn/mw690/002jW8tbzy7gbSOqZFH5d&amp;690"
                             name="image_operate_78741511956851817"></a><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOtz7C9c"
        target="_blank"><img src="http://s13.sinaimg.cn/mw690/002jW8tbzy7gbSOtz7C9c&amp;690"
                             name="image_operate_14581511956861801"></a><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOtz7C9c"
        target="_blank"><img src="http://s13.sinaimg.cn/mw690/002jW8tbzy7gbSOtz7C9c&amp;690"
                             name="image_operate_14581511956861801"></a><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOqZFH5d"
        target="_blank"><img src="http://s14.sinaimg.cn/mw690/002jW8tbzy7gbSOqZFH5d&amp;690"
                             name="image_operate_78741511956851817"></a><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOtz7C9c"
        target="_blank"><img src="http://s13.sinaimg.cn/mw690/002jW8tbzy7gbSOtz7C9c&amp;690"
                             name="image_operate_14581511956861801"></a><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd2e08ex85"
        target="_blank"><img src="http://s6.sinaimg.cn/mw690/002jW8tbzy7gd2e08ex85&amp;690"
                             name="image_operate_89361512024875922"></a><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSODSEMa0"
        target="_blank"><img src="http://s1.sinaimg.cn/mw690/002jW8tbzy7gbSODSEMa0&amp;690"
                             name="image_operate_64011511956853651"></a><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOtz7C9c"
        target="_blank"><img src="http://s13.sinaimg.cn/mw690/002jW8tbzy7gbSOtz7C9c&amp;690"
                             name="image_operate_14581511956861801"></a><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOqZFH5d"
        target="_blank"><img src="http://s14.sinaimg.cn/mw690/002jW8tbzy7gbSOqZFH5d&amp;690"
                             name="image_operate_78741511956851817"></a><span style="text-indent: 2em;">左</span><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSOqZFH5d"
        target="_blank"><img src="http://s14.sinaimg.cn/mw690/002jW8tbzy7gbSOqZFH5d&amp;690"
                             name="image_operate_78741511956851817"></a><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd2e08ex85"
        target="_blank"><img src="http://s6.sinaimg.cn/mw690/002jW8tbzy7gd2e08ex85&amp;690"
                             name="image_operate_3311512024895541"></a><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSODSEMa0"
        target="_blank"><img src="http://s1.sinaimg.cn/mw690/002jW8tbzy7gbSODSEMa0&amp;690"
                             name="image_operate_64011511956853651"></a><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSODSEMa0"
        target="_blank"><img src="http://s1.sinaimg.cn/mw690/002jW8tbzy7gbSODSEMa0&amp;690"
                             name="image_operate_64011511956853651"></a><span style="text-indent: 28px;">左</span><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gbSODSEMa0"
        target="_blank"><img src="http://s1.sinaimg.cn/mw690/002jW8tbzy7gbSODSEMa0&amp;690"
                             name="image_operate_64011511956853651"></a><a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd2e08ex85"
        target="_blank"><img src="http://s6.sinaimg.cn/mw690/002jW8tbzy7gd2e08ex85&amp;690"
                             name="image_operate_13971512024875672"></a><span style="text-indent: 2em;">右右</span></div>
<div><br></div>
<div><br></div>

<div><h3>出装选择：</h3></div>
<div><span style="text-indent: 2em;">出门：树之祭祀、治疗药膏、魔法芒果、</span><span style="text-indent: 28px;">铁树枝干</span><span
        style="text-indent: 2em;">、铁树枝干、守护指环、侦查守卫（辅助提供）</span></div>
<div><img class="item shuzhijisi">&nbsp;<img class="item zhiliaoyaogao">&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8bLHuD8f"
        target="_blank"><img src="http://s16.sinaimg.cn/mw690/002jW8tbzy7gd8bLHuD8f&amp;690"
                             name="image_operate_28841512024433719"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd84MNpfe1"
        target="_blank"><img src="http://s2.sinaimg.cn/mw690/002jW8tbzy7gd84MNpfe1&amp;690"
                             name="image_operate_32571512024566818"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd84MNpfe1"
        target="_blank"><img src="http://s2.sinaimg.cn/mw690/002jW8tbzy7gd84MNpfe1&amp;690"
                             name="image_operate_39481512024458082"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd85AG7idc"
        target="_blank"><img src="http://s13.sinaimg.cn/mw690/002jW8tbzy7gd85AG7idc&amp;690"
                             name="image_operate_35571512024458172"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd86avSw00"
        target="_blank"><img src="http://s1.sinaimg.cn/mw690/002jW8tbzy7gd86avSw00&amp;690"
                             name="image_operate_95241512024479192"></a></div>
<div><br></div>
<div><span style="text-indent: 2em;">前期：魔杖、奥术鞋、恢复头巾/治疗指环/王者之戒</span></div>
<div><a href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8jeQbNab"
        target="_blank"><img src="http://s12.sinaimg.cn/mw690/002jW8tbzy7gd8jeQbNab&amp;690"
                             name="image_operate_70581512024547616"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8k1J3G10"
        target="_blank"><img src="http://s1.sinaimg.cn/mw690/002jW8tbzy7gd8k1J3G10&amp;690"
                             name="image_operate_78871512024559300"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8pqJH927"
        target="_blank"><img src="http://s8.sinaimg.cn/mw690/002jW8tbzy7gd8pqJH927&amp;690"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8pZPmS3e"
        target="_blank"><img src="http://s15.sinaimg.cn/mw690/002jW8tbzy7gd8pZPmS3e&amp;690"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8qqRIDb3"
        target="_blank"><img src="http://s4.sinaimg.cn/mw690/002jW8tbzy7gd8qqRIDb3&amp;690"></a></div>
<div><br></div>
<div><span style="text-indent: 2em;">中期：魔杖、奥术鞋、梅肯斯姆/挑战头巾，闪烁匕首</span></div>
<div><a href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8jeQbNab"
        target="_blank"><img src="http://s12.sinaimg.cn/mw690/002jW8tbzy7gd8jeQbNab&amp;690"
                             name="image_operate_70581512024547616"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8k1J3G10"
        target="_blank"><img src="http://s1.sinaimg.cn/mw690/002jW8tbzy7gd8k1J3G10&amp;690"
                             name="image_operate_11161512024639711"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8krYhncd"
        target="_blank"><img src="http://s14.sinaimg.cn/mw690/002jW8tbzy7gd8krYhncd&amp;690"
                             name="image_operate_66551512024548599"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8kYJakd4"
        target="_blank"><img src="http://s5.sinaimg.cn/mw690/002jW8tbzy7gd8kYJakd4&amp;690"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8lt8w58d"
        target="_blank"><img src="http://s14.sinaimg.cn/mw690/002jW8tbzy7gd8lt8w58d&amp;690"
                             name="image_operate_8281512024528113"></a><br></div>
<div><span style="text-indent: 2em;"><br></span></div>
<div><span style="text-indent: 2em;">后期：卫士胫甲、洞察烟斗、希瓦的守护、闪烁匕首、刷新球、玲珑心、恐鳌之心、辉耀</span></div>
<div><a href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8vh0Ojd7"
        target="_blank"><img src="http://s8.sinaimg.cn/mw690/002jW8tbzy7gd8vh0Ojd7&amp;690"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8A1CND15"
        target="_blank"><img src="http://s6.sinaimg.cn/mw690/002jW8tbzy7gd8A1CND15&amp;690"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8AC2Ur03"
        target="_blank"><img src="http://s4.sinaimg.cn/mw690/002jW8tbzy7gd8AC2Ur03&amp;690"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8AWDgO5e"
        target="_blank"><img src="http://s15.sinaimg.cn/mw690/002jW8tbzy7gd8AWDgO5e&amp;690"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8BjkTqb4"
        target="_blank"><img src="http://s5.sinaimg.cn/mw690/002jW8tbzy7gd8BjkTqb4&amp;690"
                             name="image_operate_40311512024772177"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8BZdoNdd"
        target="_blank"><img src="http://s14.sinaimg.cn/mw690/002jW8tbzy7gd8BZdoNdd&amp;690"
                             name="image_operate_76121512024772197"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8FqQOy0e"
        target="_blank"><img src="http://s15.sinaimg.cn/mw690/002jW8tbzy7gd8FqQOy0e&amp;690"
                             name="image_operate_36081512024810365"></a>&nbsp;<a
        href="http://blog.pictures.sina.com.cn/showpic.html#url=http://album.sina.com.cn/pic/002jW8tbzy7gd8FIa4zb3"
        target="_blank"><img src="http://s4.sinaimg.cn/mw690/002jW8tbzy7gd8FIa4zb3&amp;690"
                             name="image_operate_40371512024810560"></a></div>
<br>
<div><br></div>
<div><br></div>

<div><h3>打法：</h3></div>
<div>前期凭借外壳和锚击减伤，可以试试强混烈士路。</div>
<div>如果烈士路实在混不了，就转战野区。</div>
<div>中期有大招就跟随队友一起推进。</div>
<div>
    后期团战，没有跳刀的潮汐就站在队伍的最前排做肉盾（但是潮汐后期跳刀为必备道具），有跳刀的潮汐可以躲在阴影处找准机会给与对面一击毁灭性的跳大。
</div>
<div><br></div>


<script>
    var str_init = 22;
    var int_init = 16;
    var agi_init = 15;
    var str_up = 3.30;
    var int_up = 1.70;
    var agi_up = 1.50;
    var health_init = 200;
    var mana_init = 75;
    var attack_min = 25;
    var attack_max = 31;
    var attack_speed_init = 100;
    var speed_init = 305;
    var attack_rate = 1.700000;
    var armor_init = 1;
    var attack_range_init = 150;
    var magic_resistance_init = 25;

    var main_attr = 1;

    $(function () {
        $("#str").text(str_init);
        $("#int").text(int_init);
        $("#agi").text(agi_init);
        $("#attack_speed").text(attack_speed_init + agi_init);
        $("#armor").text((armor_init + agi_init / 6).toFixed(1));
        $("#health").text(health_init + str_init * 20);
        $("#mana").text(mana_init + int_init * 12);
        if (main_attr == 1) {
            $("#attack").text(String(attack_min + str_init) + " - " + String(attack_max + str_init));
            $("#state_resistance").text((str_init * 0.15).toFixed(2));
            $(".state_resistance").show();
        } else if (main_attr == 2) {
            $("#attack").text(String(attack_min + int_init) + " - " + String(attack_max + int_init));
        } else {
            $("#attack").text(String(attack_min + agi_init) + " - " + String(attack_max + agi_init));
        }
        $("#magic_increase").text((int_init * 0.07).toFixed(2));
        $("#health_recover").text((str_init * 0.7).toFixed(1));
        $("#mana_recover").text(int_init * 2);
        $("#speed").text(speed_init);
        $("#attack_range").text(attack_range_init);
        $("#magic_resistance").text(magic_resistance_init);
        
        $("#level").change(function(){
            var value = parseInt($("#level").val());
            var str_now = str_init + str_up * (value - 1);
            var int_now = int_init + int_up * (value - 1);
            var agi_now = agi_init + agi_up * (value - 1);
            $("#str").text(Math.round(str_now));
            $("#int").text(Math.round(int_now));
            $("#agi").text(Math.round(agi_now));
            if (main_attr == 1) {
                $("#attack").text(String(attack_min + Math.round(str_now)) + " - " + String(attack_max + Math.round(str_now)));
                $("#state_resistance").text(( Math.round(str_now) * 0.15).toFixed(2));
                $(".state_resistance").show();
            } else if (main_attr == 2) {
                $("#attack").text(String(attack_min + Math.round(int_now)) + " - " + String(attack_max + Math.round(int_now)));
            } else {
                $("#attack").text(String(attack_min + Math.round(agi_now)) + " - " + String(attack_max + Math.round(agi_now)));
            }
            $("#health").text(health_init + Math.floor(str_now) * 20);
            $("#mana").text(mana_init + Math.floor(int_now) * 12);
            $("#armor").text((armor_init + agi_now / 6).toFixed(1));
            $("#attack_speed").text(attack_speed_init + Math.round(agi_now));
            $("#magic_increase").text((int_now * 0.07).toFixed(2));
            $("#health_recover").text((str_now * 0.7).toFixed(1));
            $("#mana_recover").text((int_now * 2).toFixed(1));
        });
    });
</script>

