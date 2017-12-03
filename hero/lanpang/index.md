---
layout: default
---

<div style=""><img class="zairu" src="pictures/载入.jpeg"></div>

<div style=""><h2>食人魔魔法师（简称：蓝胖，英文简称：OM）</h2></div>
<br>

<div style=""><h3>属性（裸装）：</h3><br>

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
            <td class="state_resistance" hidden>状态抗性</td>
        </tr>
        
        <tr>
            <td><span id="magic_increase"></span>%</td>
            <td><span id="health_recover"></span>%</td>
            <td><span id="mana_recover"></span>%</td>
            <td class="state_resistance" hidden><span id="state_resistance"></span>%</td>
        </tr>

        </tbody>
    </table>

</div>

<div><br></div>
<div><br></div>

<div style=""><h3>定位：</h3></div>
<div style="">
    <img style="height:300px;width:300px" src="pictures/定位.png">
</div>
<br>
<div>
    <div>tips：食人魔魔法师大多是五号位辅助。凭着高护甲和高血量，自带控制技能和减速技能，前期是一位健身教练，后期是一个吃伤害的肉盾的作用。</div>
</div>
<div style=""><br></div>
<div style=""><br></div>

<div>
    <div><h3>技能介绍：</h3></div>
    <div>一技能：火焰爆轰<img class="skill_icon" src="pictures/一技能.png"></div>
    <div><br></div>
    <div>
        <img src="pictures/一技能介绍.png">
    </div>
</div>
<div><br></div>
<div>tips：</div>
<div>
    <div>1、因为技能等级提升并不会增加眩晕时间，只会增加伤害和耗蓝，所以前期建议只学一级。</div>
    <div>2、因为技能的施法距离非常近，如果经济和局势允许，可以购买闪烁匕首或者原力法杖，增加英雄的机动性，能更容易的眩晕到对手。</div>
</div>
<div><br></div>
<div><br></div>

<div>二技能：引燃<img class="skill_icon" src="pictures/二技能.png"></div>
<div><br></div>
<div>
    <img src="pictures/二技能介绍.png">
</div>
<div><br></div>
<div>tips：</div>
<div>
    <div>1、技能耗蓝少，等级越高，伤害高，减速持续时间越久，建议主加。</div>
    <div>2、随着大招的升级，二技能变成一个范围伤害+减速的技能，能用二技能推线或者打野。</div>
</div>
<div><br></div>
<div><br></div>

<div>三技能：嗜血术<img class="skill_icon" src="pictures/三技能.png"></div>
<div><br></div>
<div>
    <img src="pictures/三技能介绍.png">
</div>
<div><br></div>
<div>tips：</div>
<div>
    <div>1、满级嗜血术能增加16%移速，相当于装备了价值2400的远行鞋。</div>
    <div>2、满级嗜血术能增加60攻速，相当于多使用了一个价值4000的银月之晶。</div>
    <div>3、所以，己方carry相当于比对面多两个装备。嗜血术是一个非常值钱的技能，建议主加。</div>
</div>
<div><br></div>
<div><br></div>

<div>四技能：多重施法<img class="skill_icon" src="pictures/四技能.png"></div>
<div><br></div>
<div>
    <img src="pictures/四技能介绍.png">
</div>
<div><br></div>
<div>tips：</div>
<div>
    <div>1、大招为食人魔魔法师的核心技能。但是，运气好的人，次次都是多重施法；运气差的人，三级大招也只有一重施法。</div>
    <div>2、1级大招最高只有二重施法；2级大招最高只有三重施法；3级大招最高有四重施法。</div>
</div>
<div><br></div>
<div><br></div>

<div>
    <div><h3>技能加点：</h3></div>
    <div>
        <div>1、主三技能，全程帮大哥增加移速攻速，更快打钱发育，增加战斗力。副二技能，增加中期输出。</div>
        <div><img class="skill_icon" src="pictures/二技能.png"><img class="skill_icon" src="pictures/三技能.png"><img class="skill_icon" src="pictures/一技能.png"><img class="skill_icon" src="pictures/三技能.png"><img class="skill_icon" src="pictures/三技能.png"><img class="skill_icon" src="pictures/四技能.png"><img class="skill_icon" src="pictures/三技能.png"><img class="skill_icon" src="pictures/二技能.png"><img class="skill_icon" src="pictures/二技能.png"><img class="skill_icon" src="pictures/二技能.png"><img class="skill_icon" src="pictures/四技能.png"><img class="skill_icon" src="pictures/一技能.png"><img class="skill_icon" src="pictures/一技能.png"><img class="skill_icon" src="pictures/一技能.png"><img class="skill_icon" src="pictures/四技能.png"></div>
        <br>
        <div>2、主二技能，增加全程对对方英雄线上的骚扰能力。副三技能，中后期为大哥增加输出移速攻速，更快打钱发育，增加战斗力。</div>
        <div><img class="skill_icon" src="pictures/三技能.png"><img class="skill_icon" src="pictures/二技能.png"><img class="skill_icon" src="pictures/一技能.png"><img class="skill_icon" src="pictures/二技能.png"><img class="skill_icon" src="pictures/二技能.png"><img class="skill_icon" src="pictures/四技能.png"><img class="skill_icon" src="pictures/二技能.png"><img class="skill_icon" src="pictures/三技能.png"><img class="skill_icon" src="pictures/三技能.png"><img class="skill_icon" src="pictures/三技能.png"><img class="skill_icon" src="pictures/四技能.png"><img class="skill_icon" src="pictures/一技能.png"><img class="skill_icon" src="pictures/一技能.png"><img class="skill_icon" src="pictures/一技能.png"><img class="skill_icon" src="pictures/四技能.png"></div>
        <br>
        <div>3、一二对点，自己打法术爆发。（酱油蓝胖不建议这样加点。）</div>
        <div><img class="skill_icon" src="pictures/一技能.png"><img class="skill_icon" src="pictures/二技能.png"><img class="skill_icon" src="pictures/一技能.png"><img class="skill_icon" src="pictures/二技能.png"><img class="skill_icon" src="pictures/一技能.png"><img class="skill_icon" src="pictures/四技能.png"><img class="skill_icon" src="pictures/一技能.png"><img class="skill_icon" src="pictures/二技能.png"><img class="skill_icon" src="pictures/二技能.png"><img class="skill_icon" src="pictures/三技能.png"><img class="skill_icon" src="pictures/四技能.png"><img class="skill_icon" src="pictures/三技能.png"><img class="skill_icon" src="pictures/三技能.png"><img class="skill_icon" src="pictures/三技能.png"><img class="skill_icon" src="pictures/四技能.png"></div>
    </div>
    <br>
</div>
<div><br></div>
<div><br></div>

<div><h3>天赋：</h3></div>
<div><img src="pictures/天赋.png"></div>
<div>
    <div>10级：作为一个五号位酱油，选择右边的加钱天赋没毛病。如果你不爱钱，那就选择左边的加施法距离吧。</div>
    <div>15级：有血加血！而且也不指望酱油蓝胖上去打普攻输出，建议加左边天赋。</div>
    <div>20级：加左边就相当于为队友每个人多出一个价值2000的振奋宝石。加右边则自己更肉。推荐加左边。</div>
    <div>25级：欧皇推荐加左边，普通推荐加右边。</div>
</div>
<div><br></div>
<div><br></div>

<div><h3>出装选择：</h3></div>
<div>出门：树之祭祀、魔法芒果、动物信使、侦查守卫、岗哨守卫、诡计之雾</div>
<div>
    <img class="item shuzhijisi">&nbsp;
    <img class="item mofamangguo">&nbsp;
    <img class="item dongwuxinshi">&nbsp;
    <img class="item zhenchashouwei">&nbsp;
    <img class="item gangshaoshouwei">&nbsp;
    <img class="item guijizhiwu">&nbsp;
</div>
<div><br></div>
<div>前期：速度之靴、淬毒之珠、魔杖、风灵之纹、影之灵龛、侦查守卫、诡计之雾</div>
<div>
    <img class="item suduzhixue">&nbsp;
    <img class="item cuiduzhizhu">&nbsp;
    <img class="item mozhang">&nbsp;
    <img class="item fenglinigzhiwen">&nbsp;
    <img class="item yingzhilingkan">&nbsp;
    <img class="item zhenchashouwei">&nbsp;
    <img class="item guijizhiwu">&nbsp;
</div>
<div><br></div>
<div>中期：静谧之鞋、淬毒之珠、魔杖、魂之灵瓮、原力法杖/微光披风</div>
<div>
    <img class="item jingmizhixie">&nbsp;
    <img class="item cuiduzhizhu">&nbsp;
    <img class="item mozhang">&nbsp;
    <img class="item hunzhilingweng">&nbsp;
    <img class="item yuanlifazhang">&nbsp;
    <img class="item weiguangpifeng">&nbsp;
</div>
<div><br></div>
<div>后期：远行鞋、洞察烟斗、希瓦的守护、魂之灵瓮、清莲宝珠、原力法杖、微光披风、炎阳纹章</div>
<div>
    <img class="item yuanxingxie">&nbsp;
    <img class="item dongchayandou">&nbsp;
    <img class="item xiwadeshouhu">&nbsp;
    <img class="item hunzhilingweng">&nbsp;
    <img class="item qinglianbaozhu">&nbsp;
    <img class="item yuanlifazhang">&nbsp;
    <img class="item weiguangpifeng">&nbsp;
    <img class="item yanyangwenzhang">&nbsp;
</div>
<div><br></div>
<div><br></div>

<div><h3>打法：</h3></div>
<div>对线期，帮助中路英雄压制对方中单，有控制、有减速，自身又是高血量、高护甲，可以让对方中单混的很难受。</div>
<div>前中期有了静谧之鞋和风灵之纹，利用高机动性赶往任何一处站场。有了影之灵龛还能增加续航。</div>
<div>积极的为己方大哥提供嗜血术buff，增加大哥打钱速度。</div>
<div>后期主要提供控制和减速，并为大哥吸收火力，出一些保护队友的装备，保护大哥不被对面先手秒杀。</div>
<div><br></div>


<script>
    var str_init = 23;
    var int_init = 17;
    var agi_init = 14;
    var str_up = 3.50;
    var int_up = 2.00;
    var agi_up = 1.50;
    var health_init = 200;
    var mana_init = 75;
    var attack_min = 41;
    var attack_max = 47;
    var attack_speed_init = 100;
    var speed_init = 290;
    var attack_rate = 1.700000;
    var armor_init = 6;
    var attack_range_init = 150;
    var magic_resistance_init = 25;

    var main_attr = 2;

    $(function () {
        $("#str").text(str_init);
        $("#int").text(int_init);
        $("#agi").text(agi_init);
        $("#attack_speed").text(attack_speed_init + agi_init);
        $("#armor").text((armor_init + agi_init / 6).toFixed(1));
        $("#health").text(health_init + str_init * 20);
        $("#mana").text(mana_init + int_init * 12);
        $("#magic_resistance").text(magic_resistance_init);
        if (main_attr == 1) {
            $("#attack").text(String(attack_min + str_init) + " - " + String(attack_max + str_init));
            $("#state_resistance").text((str_init * 0.15).toFixed(2));
            $(".state_resistance").show();
        } else if (main_attr == 2) {
            $("#attack").text(String(attack_min + int_init) + " - " + String(attack_max + int_init));
            $("#magic_resistance").text( ((1 -  (1 - magic_resistance_init / 100) * (1 - int_init * 0.15 / 100)) * 100).toFixed(1) )
        } else {
            $("#attack").text(String(attack_min + agi_init) + " - " + String(attack_max + agi_init));
            $("#speed").text( (speed_init * ( 1 + agi_init * 0.0006)).toFixed(1) )
        }
        $("#magic_increase").text((int_init * 0.07).toFixed(2));
        $("#health_recover").text((str_init * 0.7).toFixed(1));
        $("#mana_recover").text(int_init * 2);
        $("#speed").text(speed_init);
        $("#attack_range").text(attack_range_init);
        
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
                $("#magic_resistance").text( ((1 -  (1 - magic_resistance_init / 100) * (1 - int_now * 0.15 / 100)) * 100).toFixed(1) )
            } else {
                $("#attack").text(String(attack_min + Math.round(agi_now)) + " - " + String(attack_max + Math.round(agi_now)));
                $("#speed").text( (speed_init * ( 1 + agi_now * 0.0006)).toFixed(1) )
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