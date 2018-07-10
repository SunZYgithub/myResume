# 微信小程序 个人简历
此项目纯属仿照一些比较主流的简历模板框架所练习的一个小程序，比较简单实用，感兴趣的童鞋可以学习一下，希望对您有所帮助。
## 优点
1、简单实用，您使用的话可直接修改LocalData.js里面静态数据<br/>
2、拓展性强，您可以自由添加模块<br/>
3、发布成功后可直接搜索简历，‘***的个人简历’
## 使用方法
将代码down下来（`git clone https://github.com/SunZYgithub/myResume`），使用`微信开发者工具`打开,找到
* utils  
  * LocalData.js<br>
data配置项文件，修改为你自己的数据即可。<br/><br/>
![](https://github.com/SunZYgithub/myResume/raw/master/images/img/data.png "配置文件位置")
## 配置文件说明
```{
const LocalData = {
  isShowContact: true, //是否显示联系方式
  workList: [ //工作经验
    {
      title: '信义玻璃（2016年12月 ~ 至今）',
      projectList: [
        {
          projectName: '内部流程项目',
          duty: '前端界面开发（vue全家桶）',
          info: '内部工作日志项目。',
          skill: 'Java,Vue'
        },
        {
          projectName: '汽玻在线下单平台（Java web）',
          duty: '前台架构，PC端前端业务代码,java,后期的维护',
          info: '基于ebs的订单下单系统',
          skill: 'Java,ES6,Webpack'
        },
        {
          projectName: '信义储能',
          duty: '负责项目后期维护',
          info: '信义储能官网',
          skill: '前端Php'
        }
       
      ],
    },
    {
      title: '北京时代创信科技有限公司（2016年6月 ~ 2016月11月）',
      projectList: [
        {
          projectName: '上海福利彩票即开票系统',
          duty: '前台架构，组件二次封装，封装自有UI库',
          info: '彩票行业，本系统囊括即开票（刮刮乐）的整个生命周期，主要包含：创建、印刷、分发、调拨、兑奖、销毁等。',
          skill: 'Java,Jquery,Pjax'
        },
        {
          projectName: '蓝熙健康、绿城健康社区',
          duty: '前端页面开发，组件二次封装，编写开发文档',
          info: '医疗行业，使用相关检测设备（血糖仪，血压仪等）检测之后上传到云端，再推送到设备的关注者，让关注者实时了解使用的数据。 以此衍生附属功能，比如月度报表、分析数据并给出改善病情的建议、专属家庭医生和健康管理师实时解答相关问题等功能。',
          skill: 'Java,Jquery,ajax'
        },

      ],
    }
   
  ],
  baseInfo: { //基础信息
    enName: 'Szy', //英文名
    title: 'WEB Engineer',  //职位英文名
    nameAndSex: '孙智勇 / 男', //中文名/性别
    birthday: '1993/8/26', //生日
    diplomaAndSchool: '本科 / 山东理工大学电气工程系', //学历/学校
    workAge: '2年', //工作年限
    location: '东莞',  //工作地点
    wantPosition: '前端工程师', //期望职位
    salary: '7K ~ 10K', //期望薪酬
    mobilePhone: '15001738162',//移动手机
    email: '13925838663@163.com',//邮箱
    wechatNo: 'SunZY1993',//微信号
    github: '@SunZYgithub', //github 用户名
    githubUrl: 'https://github.com/SunZYgithub', //github主页
  },
  skillList: [  //技能清单
    'Web开发：Java / NodeJs',
    'Web框架：bootstrap/ express',
    'CSS框架：Bootstrap / PureCSS / SASS',
    'JS框架：Jquery / AngularJS / Vue',
    '构建工具：Webpack  / Grunt ',
    '数据库相关：MySQL / Oracle ',
    '版本管理：Svn / Git',
    '微信： 小程序开发',
  ],
  starList: [ //技能关键字start 1-5
    { name: 'JavaScript', star: 4 },
    { name: 'Css3', star: 4 },
    { name: 'Html5', star: 4 },
    { name: 'Jquery', star: 4 },
    { name: 'Bootstrap', star: 4 },
    //{ name: 'Cordova', star: 4 },
    { name: 'Git/SVN', star: 4 },
    //{ name: 'Charts', star: 4 },
    { name: 'Webpack', star: 3 },
    //{ name: 'AngularJS', star: 3 },
    { name: 'Vue', star: 3 },
    { name: 'Java', star: 3 },
    { name: 'Ionic', star: 3 },
    { name: 'NodeJs', star: 2 },
    { name: 'Oracle', star: 2 },
    { name: 'React', star: 2 }
  ]
};
module.exports = LocalData
```
## 其它
希望通过这个小项目能对您有所帮助，祝您早日找到自己心仪的工作。<br/>
如果对您有所帮助，请在右上角给我一个 ***Star***
## 小程序学习链接
[微信小程序简易教程]（https://developers.weixin.qq.com/miniprogram/dev/ )
