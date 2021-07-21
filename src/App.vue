<template>
  <div id="app">
    <div class="header">
      <h1>暴雨救援，河南加油！</h1>
    </div>
    <div class="body">
      <div class="container">
        <van-tabs v-model="active" color="#3373DD" sticky>
          <van-tab title="救援电话">
            <div class="tab-content">
              <table class="tg">
                <thead>
                  <tr>
                    <th class="tg-u1yq" colspan="2">郑州市5支</th>
                  </tr>
                </thead>
                <tbody>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">郑州市红十字水上义务救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13938568990">牛振西 13938568990</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">郑州红十字蓝天应急救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13838332525">李志则 13838332525</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">河南省应急救援协会</td>
                    <td class="tg-0lax">
                      <a href="tel:13838336788">陈水全 13838336788</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">新郑市神鹰救援队</td>
                    <td class="tg-0lax">
                      <span style="font-weight: 400; font-style: normal"
                        ><a href="tel:13253381110">吴国钦 13253381110</a></span
                      >
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">新郑巾蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13733199101">秦军峰 13733199101</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">开封市3支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">开封蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13837835001">张海祥 13837835001</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">开封市无线电协会应急通信大 队</td>
                    <td class="tg-0lax">
                      <a href="tel:18503781818">康伟 18503781818</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">开封市红豹救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:18803789668">柒倩倩 18803789668</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">洛阳市3支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">洛阳市神龙水上义务搜救队</td>
                    <td class="tg-0lax">
                      <a href="tel:15670399937">杨红山 15670399937</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">洛阳市神鹰救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:15538837110">张超伟 15538837110</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">伊川县神鹰救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:15036999699">梁绪伟 15036999699</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">平顶山市3支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">平顶山市永安应，急救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13949469283">杜全甫 13949469283</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">救援协会郊县应急队</td>
                    <td class="tg-0lax">
                      <a href="tel:13383999505">何邵舟 13383999505</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">义工联合蓝大救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:17335236002">李伟峰 17335236002</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">安阳市4支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">红旗渠应急救援中心</td>
                    <td class="tg-0lax">
                      <a href="tel:18567769958">杨水峰 18567769958</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">内黄县枣乡应急救援中心</td>
                    <td class="tg-0lax">
                      <a href="tel:15890758666">朱志刚 15890758666</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">林州市蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13603461315">杨志军 13603461315</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">滑县应急敕援协会</td>
                    <td class="tg-0lax">
                      <a href="tel:18637288000">赵彦军 18637288000</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">鹤壁市2支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">淇县斑马救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:17630396099">韦玉其 17630396099</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">山城区无疆公靛救援协会</td>
                    <td class="tg-0lax">
                      <a href="tel:17719900007">钱宏滔 17719900007</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">新乡市2支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">新乡市河马应急救援中心</td>
                    <td class="tg-0lax">
                      <a href="tel:13333804449">柴守勇 13333804449</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">退役军人应急救援中心</td>
                    <td class="tg-0lax">
                      <a href="tel:13525022282">刘海军 13525022282</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">焦作市2支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">焦作市应急救援协会</td>
                    <td class="tg-0lax">
                      <a href="tel:18623911479">张昊 18623911479</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">温县应急救援服务中心</td>
                    <td class="tg-0lax">
                      <a href="tel:15036520006">张彦兵 15036520006</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">濮阳市4支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">濮阳市红十字救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13839396699">刘冠中 13839396699</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">濮阳市中安众联应急救援服务中</td>
                    <td class="tg-0lax">
                      <a href="tel:13030314598">徐兴斌 13030314598</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">濮阳市工程机械行业办会应急救</td>
                    <td class="tg-0lax">
                      <a href="tel:13503938576">丁建国 13503938576</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">清丰县“红十字”应急救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13513935088">朱志芳 13513935088</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">许昌市5支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">许昌市应急救援协会</td>
                    <td class="tg-0lax">
                      <a href="tel:13903990656">高煜 13903990656</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">许昌市工程机械行业办会</td>
                    <td class="tg-0lax">
                      <a href="tel:15937455885">胡结实 15937455885</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">长葛市红十字志愿者办会</td>
                    <td class="tg-0lax">
                      <a href="tel:13462165087">胥忠义 13462165087</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">禹州市应急救援协会</td>
                    <td class="tg-0lax">
                      <a href="tel:13937458259">工俊峰 13937458259</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">许昌市魏都区蓝天救父队</td>
                    <td class="tg-0lax">
                      <a href="tel:13849890188">俎小娟 13849890188</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">溪河市5支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">中青应急救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:18803950088">信天游 18803950088</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">潦河水上船员忐愿者力会</td>
                    <td class="tg-0lax">
                      <a href="tel:18939547555">张红锋 18939547555</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">渥河市无线电协会</td>
                    <td class="tg-0lax">
                      <a href="tel:18639533339">江世奇 18639533339</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">涡河市业余尢致电运动协会</td>
                    <td class="tg-0lax">
                      <a href="tel:13503952586">翟阳阳 13503952586</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">临颍蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13603171997">翟身 13603171997</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">南阳市3支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">城区蓝天救援中心</td>
                    <td class="tg-0lax">
                      <a href="tel:15688112117">范海涛 15688112117</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">镇平县蓝犬救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13937707520">张界 13937707520</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">桐柏监大救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13598233396">刘博 13598233396</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">商丘市3支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">商丘市水上义务救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13700830066">黄伟 13700830066</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">商丘市磕天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13837034774">王勇 13837034774</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">
                      商丘市汽车摩托车运动协会（越 野。族）
                    </td>
                    <td class="tg-0lax">
                      <a href="tel:13598398898">桂强 13598398898</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">信阳市5支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">信阳市蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13603761722">段忠强 13603761722</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">淮滨县蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13803765810">暗史 13803765810</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">潢川县蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:15637661000">陈俊 15637661000</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">固始蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:18348477555">陶明洋 18348477555</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">固始神州救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:15537652283">任光磊 15537652283</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-u1yq" colspan="2">周口市5支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">周口蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:138386G8228">朱健康 138386G8228</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">项城应急蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:17633979958">张海广 17633979958</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">项城水卜义务救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:李建国 13938060537">李建国 13938060537</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">鹿邑神鹰救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13460D20166">张正江 13460D20166</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">周口川汇蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:15346090666">盂坤 15346090666</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-qh0q" colspan="2">驻马店市8支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">负责人及手机号</td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">驻马店市红十字蛟龙水上应急搜</td>
                    <td class="tg-0lax">
                      <a href="tel:13598903988">赵亚洲 13598903988</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">驻马店市蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:17339671661">李振 17339671661</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">驻马店市红十字会山地救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:15036911069">段国富 15036911069</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">泌阳县红十字蛟龙应急救援队+</td>
                    <td class="tg-0lax">
                      <a href="tel:17633893777">平恩东 17633893777</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">泌阳县蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13097097888">王建磊 13097097888</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">西平县至善公拉志愿者协会蚊龙</td>
                    <td class="tg-0lax">
                      <a href="tel:15893908715">耿广德 15893908715</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">汝南真和工字蛟龙义务救援志冠</td>
                    <td class="tg-0lax">
                      <a href="tel:13839636415">胡汝生 13839636415</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">上蔡蓝天救援队</td>
                    <td class="tg-0lax">
                      <a href="tel:13949564518">未卜 13949564518</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-qh0q" colspan="2">济源示范区2支</td>
                  </tr>
                  <tr>
                    <td class="tg-1wig">队伍名称</td>
                    <td class="tg-1wig">
                      <span style="font-weight: 700; font-style: normal"
                        >负责人及手机号</span
                      >
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">济源市红十字应急救丧队</td>
                    <td class="tg-0lax">
                      <a href="tel:13303910588">关永科 13303910588</a>
                    </td>
                  </tr>
                  <tr>
                    <td class="tg-0lax">济源市应急救援协会</td>
                    <td class="tg-0lax">
                      <a href="tel:18790020089">吕涛 18790020089</a>
                    </td>
                  </tr>
                </tbody>
              </table>
              <p class="source">
                来自：<a href="https://weibo.com/u/2803301701">@人民日报</a>
              </p>
            </div>
          </van-tab>
          <van-tab title="自救指南"
            ><div class="tab-content">
              <van-collapse v-model="activeNames">
                <van-collapse-item title="自救事项" name="1">
                  <div class="post-content">
                    <p>
                      来自：<a href="https://weibo.com/u/3215848574">@老张哇</a>
                    </p>
                    <ol>
                      <li>看到无人机记得打开手电筒挥舞!会确定方向!</li>
                      <li>
                        来了例假的女生要注意!不到万不得已不要淌水!完了之后记得去医院检查!
                      </li>
                      <li>
                        水里会裹挟垃圾、动物尸体、地上的细菌等等，如果有在外大面积接触过雨水、泥水的河南朋友回到家后一定要清洁身体，把家里的备用药品找出来以防万一。
                      </li>
                      <li>
                        衣服裤子可以改装成救生圈，长袖衣服把袖口、裤口扎住，打湿后吹气就可以。短袖体洫把上下两端扎住，打湿吹气也能当救生圈----注意要留下吹气的口，衣服会缓慢漏气，只要时不时吹气补充就可以。
                        (是冲锋衣材质的才能有效果，其他透气性较强的衣物请慎重,雪纺衫，衬衣面料效果较好，棉质体恤较差
                      </li>
                      <li>
                        如果被困不要想着试一试冲出去可以去到安全的地方越高的地方越安全!就在原地尽量往高处等着救援
                      </li>
                      <li>
                        不能喝自来水
                        水的质量可能不达标！有条件就喝瓶装水！！或者烧开的水！！
                      </li>
                      <li>
                        给所有充电宝、手机充满电。（一旦停电，就停止刷手机，家庭成员手机每次开一个，保持畅通、关注天气预报、险情预警等信息）
                      </li>
                      <li>接足饮用水，并将家里的食物和饮用水放在高处。</li>
                      <li>
                        住在低处或一楼的姐妹，睡前身边放置几个大一些的盆或木板。(尽量不要用盆容易打翻！木板！木板！实在不行拆木质门板！
                      </li>
                      <li>
                        非必要尽量不要出门，如果蹚水，一定注意防触电防塌陷防围墙倒塌
                      </li>
                      <li>如遇险情，可发到微博，人多办法多希望就多。</li>
                      <li>
                        记得，不要穿拖鞋凉鞋，不跟脚的鞋子，进水雨靴千万别穿一旦灌水，根本走不了，穿运动鞋！
                      </li>
                    </ol>
                  </div>
                </van-collapse-item>
                <van-collapse-item title="暴雨紧急求助通道" name="2">
                  <div class="post-content">
                    <p>
                      来自：<a href="https://weibo.com/u/2803301701"
                        >@人民日报</a
                      >
                    </p>
                    <img
                      src="https://i.loli.net/2021/07/21/m8KwpjesSgYhfvR.jpg"
                      alt=""
                    />
                  </div>
                </van-collapse-item>
                
                <van-collapse-item title="暴雨避险指南" name="3">
                  <div class="post-content">
                    <p>
                      来自：<a href="https://weibo.com/u/2803301701"
                        >@人民日报</a
                      >
                    </p>
                    <img
                      src="https://i.loli.net/2021/07/21/faMnz9LqsxJRrKI.jpg"
                      alt=""
                    />
                  </div>
                </van-collapse-item>
                <van-collapse-item title="洪水自救指南" name="4"
                  ><div class="post-content">
                    <p>
                      来自：<a
                        href="https://www.zhihu.com/question/473592745/answer/2010364602"
                        >@壹基金</a
                      >
                    </p>
                    <p>
                      夏季为洪水高发期，洪涝灾害极易威胁人民群众的生命财产安全，也易影响环境，造成疾病的传播。洪水来临时如何最大限度保护我们的家，遇到洪涝灾害又该怎样来保护自己和亲人的生命安全呢？
                    </p>
                    <h3 id="一怎样做好预防措施">
                      <strong>一、怎样做好预防措施：</strong>
                    </h3>
                    <p>
                      1.
                      随时关注本地新闻和天气预报，做好应对停电、停水、停气的准备。接到洪水预警预报信息，应备足食品、衣物、饮用水、生活日用品和必要的医疗用品，妥善安置家庭贵重物品。
                    </p>
                    <p>
                      2.
                      保存好尚能使用的通信设备。收集手电、口哨、镜子、打火机、色彩艳丽的衣服等可作为信号用的物品，做好被救援的准备。
                    </p>
                    <p>
                      3.
                      如果可能需要外出避难，应至少准备一个可随身带出的应急包，应急包中的物资要考虑到不同家庭成员的特殊需求，例如婴儿用品、慢性病药物等。
                    </p>
                    <p>
                      4.
                      制订家庭应急预案：根据政府和气象部门的预警，可能面临选择转移安置，待在家里避险，或者投亲靠友等应对办法，应提前全家商议达成共识，尽量保障灾时全家人在一起，如果不在一起时，可到约定的安全地点集合。
                    </p>
                    <p>
                      5.
                      在室内避险，要注意关闭电源、气阀和水管，提前储备足够的干净水、食物以及其它备灾物资。
                    </p>
                    <p>
                      6.
                      随时做好安全转移的准备，选择最佳路线和目的地撤离。在不得不撤离时，准备好能自救逃生的工具。也可以搜集木盆、木材、大件泡沫塑料等适合漂浮的材料，加工成救生装置以备急需。
                    </p>

                    <h3 id="二洪水来时怎样做好安全转移">
                      <strong>二、洪水来时怎样做好安全转移：</strong>
                    </h3>
                    <p>1. 洪水来临，要尽快离开地势低洼处，向高处转移避险。</p>
                    <p>
                      2.
                      在积水路面行走，一定要穿系带的运动鞋，并把鞋带系紧。不要穿雨靴，雨灌进雨靴就没办法自由活动了。
                    </p>
                    <p>3. 涉水行走时，可找来棍子、长柄雨伞等做探路工具</p>
                    <p>
                      4.
                      洪水来的时候开车很危险，汽车会熄火，而且当水漫过车门时，里面的人会因为车门打不开被困住。
                    </p>
                    <p>
                      5.
                      水深及腰时，就不要冒险在水中行走了，不要盲目冲动过河，这时应该找一块高地等待救援。
                    </p>

                    <h3 id="三怎样做好房屋保护措施">
                      <strong>三、怎样做好房屋保护措施：</strong>
                    </h3>
                    <p>
                      1.
                      为防止洪水涌入室内，可用沙袋和塑料布在门口等处堆砌挡水墙，如有必要窗台外也需要挡水墙。
                    </p>
                    <p>2. 将家具和贵重物品移至安全的地方，比如最高楼层。</p>
                    <p>
                      3. 将热水器和插电板等电器设备转移到不太可能被淹的位置。
                    </p>
                    <p>
                      4.
                      如果房屋难以避免被淹没，可使用大的软木塞或其它塞子塞住淋浴、浴缸、洗手盆及下水道的出水口，或者在下水管中安装止回阀，以防洪水从下水管倒流到房屋中。将车辆停放到安全地带。
                    </p>

                    <h3 id="四被洪水困住怎样求救">
                      <strong>四、被洪水困住怎样求救：</strong>
                    </h3>
                    <p>
                      1.
                      如果自己被洪水困住了，首先要想办法和外界获得联系，如果手机没被浸湿，及时打110请求专业人员的救援。在长时间的等待过程中不要忘了一直发求救信号，以免被遗忘。
                    </p>
                    <p>
                      2.
                      如果看到穿着制服的救援人员，尽量通过挥动彩色布条、吹响口哨等方式制造动静，让救援人员能够准确找到你。
                    </p>
                    <p>
                      3.
                      遇到洪水最主要的一点就是不要慌张，太过于慌张反而会让自己做错事，从而处于比较危险的状态。
                    </p>

                    <h3 id="五洪水过后安全须知">
                      <strong>五、洪水过后安全须知：</strong>
                    </h3>
                    <p>
                      1.
                      洪水过后，做好卫生防疫工作，避免发生传染病。注意不要使用被污染的水源，被蚊虫叮咬后不要乱抓，每天饭前、休息前，最好将暴露在衣服外面的皮肤做好消毒，并对环境和被褥等进行消毒。
                    </p>
                    <p>
                      2.
                      不要使用已被洪水淹没的天然气或电器。不要食用任何被洪水污染的食物。
                    </p>
                    <p>
                      3.
                      洪水过后，清理淤泥时需要穿上靴子，带上厚手套，以防淤泥中有蛇虫等伤人，或产生细菌感染。
                    </p>

                    <p>（根据国家应急广播、壹基金相关信息整理）</p>
                  </div></van-collapse-item
                >
              </van-collapse>
            </div></van-tab
          >
          <van-tab title="微博互助">
            <iframe
              width="100%"
              height="800px"
              src="https://m.weibo.cn/search?containerid=231522type%3D1%26q%3D%23%E6%B2%B3%E5%8D%97%E6%9A%B4%E9%9B%A8%E4%BA%92%E5%8A%A9%23%26t%3D3%3Fcontainerid%3D231522type%3D1%26q%3D%23%E6%B2%B3%E5%8D%97%E6%9A%B4%E9%9B%A8%E4%BA%92%E5%8A%A9%23%26t%3D3&containerid=231522type%3D1%26q%3D%23%E6%B2%B3%E5%8D%97%E6%9A%B4%E9%9B%A8%E4%BA%92%E5%8A%A9%23%26t%3D3&jumpfrom=weibocom"
              frameborder="0"
            >
            </iframe
          ></van-tab>
        </van-tabs>
      </div>
    </div>
    <div class="footer">
      <a href="https://support.qq.com/product/340224">反馈建议</a><i>·</i><a href="/wechat.png">联系作者</a>
    </div>
  </div>
</template>

<script>
import Vue from "vue";
import { Tab, Tabs, Collapse, CollapseItem } from "vant";
import "vant/lib/tab/style";
import "vant/lib/tabs/style";
import "vant/lib/collapse/style";
import "vant/lib/collapse-item/style";
Vue.use(Collapse);
Vue.use(CollapseItem);
Vue.use(Tab);
Vue.use(Tabs);

export default {
  name: "App",
  components: {},
  data() {
    return {
      activeNames: ["1"],
    };
  },
};
</script>
<style>
#app {
  font-family: "Helvetica Neue", Roboto, Arial, "PingFang SC", 思源黑体,
    "思源黑体 CN", "Source Han Sans CN", "Source Han Sans SC",
    "Hiragino Sans GB", "Microsoft Yahei", "Microsoft JhengHei", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  background: #0575e6;
  background: -webkit-linear-gradient(to top, #021b79, #0575e6);
  background: linear-gradient(to top, #021b79, #0575e6);
  min-height: 100vh;
}
.source {
  padding: 10px;
  font-size: 14px;
}
.source a {
  color: #0575e6;
}
.header {
  text-align: center;
  padding: 20px 0;
}
.header h1 {
  color: #fff;
  font-size: 30px;
  margin: 0;
  font-weight: 700;
}
.tab-content {
  padding: 0;
  background-color: #fff;
}
.container {
  padding: 0 8px;
}
.footer {
  padding: 20px 0;
  text-align: center;
  color: #fff;
  font-size: 14px;
}
.footer a {
  color: #fff;
}
.footer i {
  display: inline-block;
  margin: 0 10px;
}
.tg {
  border-collapse: collapse;
  border-spacing: 0;
  width: 100%;
}
.tg td {
  border-color: #e6e6e6;
  border-style: solid;
  border-width: 1px;
  font-family: Arial, sans-serif;
  font-size: 14px;
  overflow: hidden;
  padding: 10px 5px;
  word-break: normal;
}
.tg th {
  border-color: #e6e6e6;
  border-style: solid;
  border-width: 1px;
  font-family: Arial, sans-serif;
  font-size: 14px;
  font-weight: normal;
  overflow: hidden;
  padding: 10px 5px;
  word-break: normal;
}
.tg .tg-1wig {
  font-weight: bold;
  text-align: left;
  vertical-align: middle;
}
.tg .tg-qh0q {
  background-color: #e6e6e6;
  color: #000000;
  font-weight: bold;
  text-align: center;
  vertical-align: middle;
}
.tg .tg-u1yq {
  background-color: #e6e6e6;
  font-weight: bold;
  text-align: center;
  vertical-align: middle;
}
.tg .tg-0lax {
  text-align: left;
  vertical-align: middle;
}
.tg .tg-0lax a {
  color: #0575e6;
  font-weight: 600;
}
.van-sticky--fixed {
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.08);
}
.van-tab--active {
  font-weight: 600;
}
.post-content {
  color: #333;
}
.post-content a {
  color: #0575e6;
}
.post-content img {
  max-width: 100%;
  height: auto;
}
.post-content ol {
  list-style: auto;
  padding-left: 20px;
  margin: 1em 0;
}
.post-content li {
  margin-bottom: 10px;
}
</style>
