<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>简历</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 20px;
      background-color: #f5f5f5;
      color: #333;
      min-width: 1200px; /* 设置页面最小宽度 */
    }

    .container {
      width: 1200px;
      margin: 0 auto;
    }

    header {
      text-align: center;
      margin-bottom: 30px;
    }

    h1 {
      color: #2c3e50;
    }

    .top-row {
      display: grid;
      grid-template-columns: repeat(4, minmax(250px, 1fr));
      gap: 20px;
      margin-bottom: 30px;
    }

    .module {
      background-color: white;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s, box-shadow 0.3s;
      cursor: pointer;
      min-width: 250px; /* 双重保护 */
    }

    .module:hover {
      transform: translateY(-5px);
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.15);
    }

    .module h2 {
      color: #3498db;
      margin-top: 0;
      border-bottom: 2px solid #eee;
      padding-bottom: 10px;
      font-size: 1.2rem;
      text-align: center;
    }

    .module p {
      line-height: 1.6;
      text-align: center;
    }

    .module-icon {
      font-size: 40px;
      text-align: center;
      margin-bottom: 15px;
      color: #3498db;
    }

    .content-column {
      background-color: white;
      border-radius: 10px;
      padding: 30px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      display: none;
    }

    .content-column.active {
      display: block;
    }

    footer {
      text-align: center;
      margin-top: 40px;
      padding: 20px;
      color: #7f8c8d;
    }

    /* 移动端适配 - 当屏幕小于1200px时切换布局 */
    @media (max-width: 1200px) {
      body {
        min-width: auto;
      }

      .container {
        width: 100%;
        padding: 0 15px;
        box-sizing: border-box;
      }

      .top-row {
        grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      }
    }
  </style>
</head>
<body>
<div class="container">
  <header>
    <h1>富强  民主  文明  和谐</h1>
    <p>期望一个舞台大展拳脚</p>
  </header>

  <div class="top-row">
    <!-- 模块1 -->
    <div class="module" onclick="showContent(1)">
      <div class="module-icon">📊</div>
      <h2>个人信息</h2>
      <p>点击了解我的信息</p>
    </div>

    <!-- 模块2 -->
    <div class="module" onclick="showContent(2)">
      <div class="module-icon">🌐</div>
      <h2>工作经历</h2>
      <p>点击了解详情</p>
    </div>

    <!-- 模块3 -->
    <div class="module" onclick="showContent(3)">
      <div class="module-icon">📱</div>
      <h2>项目经历</h2>
      <p>点击了解详情</p>
    </div>

    <!-- 模块4 -->
    <div class="module" onclick="showContent(4)">
      <div class="module-icon">☁️</div>
      <h2>联系方式</h2>
      <p>点击了解详情</p>
    </div>
  </div>

  <!-- 内容列 -->
  <div id="content-1" class="content-column active">
    <h3>基本信息</h3>
    <p>向仲阳，男，土家族，1998年11月生，湖北恩施人</p>
    <ul>
      <li><strong>身高：</strong>168cm</li>
      <li><strong>体重：</strong>100kg</li>
      <li><strong>毕业院校：</strong>河北经贸大学，信息与计算科学专业</li>
      <li><strong>自我评价：</strong>积极向上，踏实勤奋</li>
    </ul>
  </div>

  <div id="content-2" class="content-column">
    <h3>工作经历及技能</h3>
    <p>专业的软硬件产品经验</p>
    <ul>
      <li><strong>2021年07月-2022年06月，深圳市视美通智能科技有限公司：</strong>产品技术支持研发部，全权负责公司关于Linux系统软件的测试、负责出货设备的调试、新品样机的安装与调试、对客户的需求进行完善等工作。接触的客户面也比较广；硬件与软件的测试，比如硬件方面有安卓主板、x86主板等、软件方面关于健康防疫、旅游景点门禁、医疗诊断等等</li>
      <li><strong>2022年06月-2022年10月，深圳市元征科技股份有限公司：</strong>对audi车型**型功能进行开发，利用现有的算法和数据协议，补全软件功能，并协助测试部门修改bug直至此功能完善。</li>
      <li><strong>2022年11月-2025年03月，深圳市视美通智能科技有限公司：</strong>负责整机开发到交付的全流程管控
        1.负责制定、实施项目进度表，管控项目启动、计划、控制、执行和收尾的时间节点;2.负责管控、处理项目中的问题、风险和变化，确保项目按时保质推向市发售;3.负责制定具体产品规格、产品执行计划并保证其得到高效高质的项目执行，负责协调解决产品生命周期中的各种问题;4.负责对接设计、生产等合作伙伴，把控产品设计进度与质量、生产过程进度与质量，控制产品良品率;
        5.负责与项目相关各类人员沟通、协调解决开发、实施、第三方合作过程中的各种问题;</li>
      <li><strong>技能总结：</strong>熟练使用常用办公软件，excel，word等；流畅使用其他软件，诸如墨刀，keil5，vs等</li>
    </ul>
  </div>

  <div id="content-3" class="content-column">
    <h3>产品项目经历</h3>
    <p>以安卓设备为主，另含有linux和X86平台设备</p>
    <ul>
      <li><strong>脉诊仪问诊设备：</strong>该项目是武汉某企业与医院合作定制的脉诊设备，主要是方便各大门店和社区的线上问诊。在此项目中，主要负责客户需求对接和设备硬件供应商对接，了解客户的需求为客户制定最优化的产品解决方案，解决设备在整合期间音频模块与七牛云平台的适配问题、软件使用流程规范化问题和塑胶开模试模等。项目历时很长，期间协调各方合作完成，最终在24年10月落地。</li>
      <li><strong>ai健康体测仪：</strong>该项目由国内某大型企业提供算法，我方完成软硬件集成。在此期间，根据客户需求反馈精准提炼，生成需求报告，调试人体成分模块、身高体重模块等硬件，并结合相关协议，生成软件运行流程文档和思维导图，供由软件工程师制作软件。针对客户使用场景，整合完善不同版本的设备外部硬件进行试产。</li>
<!--      <li><strong>用户体验设计：</strong>专注于直观、愉悦的用户体验</li>-->
<!--      <li><strong>应用商店发布：</strong>协助完成应用商店的上架流程</li>-->
    </ul>
  </div>

  <div id="content-4" class="content-column">
    <h3>有意向请联系</h3>
    <p>多年产品经验，从零到壹，认真可靠，找我准没错。</p>
    <ul>
      <li><strong>QQ：</strong>365819162@qq.com</li>
      <li><strong>手机微信同号：</strong>18872803245</li>
<!--      <li><strong>负载均衡：</strong>自动分配流量，保证高可用性</li>-->
<!--      <li><strong>安全监控：</strong>24/7监控您的云环境，防范安全威胁</li>-->
    </ul>
  </div>

  <footer>
    <p>© 2025 产品经理简历 | 联系我：365819162@qq.com</p>
  </footer>
</div>

<script>
  function showContent(moduleNumber) {
    // 隐藏所有内容列
    const allContents = document.querySelectorAll('.content-column');
    allContents.forEach(content => content.classList.remove('active'));

    // 显示选中的内容列
    const selectedContent = document.getElementById(`content-${moduleNumber}`);
    selectedContent.classList.add('active');
  }
</script>
</body>
</html>
