# Wiki Log

> 所有 wiki 操作的按时间顺序记录。仅追加。
> 格式：`## [YYYY-MM-DD HH:MM] action | subject`
> Actions: ingest, update, query, lint, create, archive, delete
> 超过500条时轮转：重命名为 log-YYYY.md，新建当前文件。

## [2026-09-18 22:00] ingest | 2026-09-17~18 每日信息整理（robert深度对话+盖世日报）

### 新建页面（2个）
- entities/terra-robotics.md - 地瓜机器人：C轮4亿美元，2026年累计融资近45亿元，旭日系列800万片出货，具身智能客户覆盖率突破50%
- concepts/dual-rotor-motor.md - 双转子电机技术：岚图/小米专利，混动系统的破局方向，压缩轴向空间+消除换挡中断

### 更新页面（9个）
- entities/stepfun.md - 新增外供困境分析（同构类比神玑芯片），李书福投资+印奇任董事长细节，极氪8X超级Eva绑定
- entities/leapmotor.md - 新增自研机器人确认（朱江明9/16披露），11年全域自研技术外溢，整车/电驱/电池技术输出详情
- concepts/humanoid-robot-industry.md - 新增优必选U1交付+5000万海外订单、零跑确认入局、蚂蚁灵波LingBot-World 2.0开源
- entities/li-auto.md - 新增全系自研电池切换计划，i6四季度搭载自研5C+马赫芯片双自研组合
- entities/nio.md - 新增纯电坚守者分析，李斌Q4渗透率70%判断，1-8月累计交付262,893台
- entities/tesla.md - 新增MPCI指标细节，中国千公里级vs百公里级差距分析
- entities/changan.md - 新增天枢领航智驾系统（央企首个一段式端到端），启源Q06预售
- entities/geely.md - 新增银河TT上市信息（12.99-18.59万/800V/6C/激光雷达），阶跃星辰绑定深度；领克欧洲独家经销
- concepts/nev-penetration-60-percent.md - 新增中汽协8月60.6%数据确认、蔚来Q4 70%预测、9月60款新车投放狂潮

### 导航更新
- index.md - 新增2页，总数50→52，更新日期至2026-09-18
- log.md - 追加本条目

### 来源
- memory/2026-09-17.md（robert深度对话+阶跃星辰分析）
- daily-news/2026-09-17-gasgoo-evening.md
- daily-news/2026-09-18-gasgoo-evening.md

### 备注
- 今日robert无直接对话，cron任务自动整理
- 核心看点：阶跃星辰外供困境（同构于神玑芯片）、地瓜机器人C轮4亿、零跑自研机器人确认、理想全面自研电池+芯片、新能源渗透率60.6%常态化、双转子电机量产可能性探讨

## [2026-07-01 22:00] create | Wiki 初始化
- Domain: 新能源汽车行业
- 创建目录结构：raw/, entities/, concepts/, comparisons/, queries/, _archive/
- 创建 SCHEMA.md、index.md、log.md
- 触发：每日Wiki知识库整理 cron 任务

## [2026-07-31 22:00] ingest | 2026-07-31 cron任务数据
- 新建实体页面：
  - entities/xiaomi-pengcheng.md - 小米汽车第二品牌，增程旗舰SUV
  - entities/zunjie.md - 华为+江淮百万级MPV品牌
- 新建概念页面：
  - concepts/range-extender-trend.md - 增程技术趋势，400km纯电续航
  - concepts/lidar-penetration.md - 激光雷达下沉至15万级
- 更新实体页面：
  - entities/byd.md - 添加大汉旗舰轿车信息（1008km续航）
- 导航更新：
  - index.md - 新增4个页面，总数更新为9
  - log.md - 追加本条目
- 来源：memory/2026-07-31.md（cron任务自动记录）

## [2026-08-06 22:00] ingest | 2026-08-06 盖世汽车晚报
- 新建概念页面：
  - concepts/l3-mandatory-standard.md - L3强制国标GB 44721—2026，责任转向车企
  - concepts/global-battery-market-2026.md - 全球动力电池格局，CATL占39.9%
- 新建实体页面：
  - entities/saic-gm.md - 上汽通用续约20年至2047年，新能源渗透率20%
- 导航更新：
  - index.md - 新增3个页面，总数更新为12
  - log.md - 追加本条目
- 来源：daily-news/2026-08-06-gasgoo-evening.md
- 备注：今日无活跃对话，仅cron任务自动执行

## [2026-08-10 22:00] ingest | 2026-08-10 汽车AI应用每日动态
- 新建实体页面：
  - entities/li-auto.md - 理想汽车：马赫M100芯片，VLA模型，12亿公里数据，AI投入60亿
- 新建概念页面：
  - concepts/vla-world-model.md - VLA+世界模型融合：端到端智驾进入“物理AI”阶段，小鹏/理想/小米三强路线对比
- 更新现有页面：
  - concepts/ai-in-automotive-rd.md - 新增：谷歌75%代码AI生成、AI测试智能体、PLM/ALM AI化、智能座舱市场1828亿
  - concepts/l3-mandatory-standard.md - 新增：车企全生命周期安全主体责任、Tier1与主机厂责任边界重构
  - entities/xpeng.md - 新增：VLA 2.0 Q3发布信息，更新关系网络
  - entities/xiaomi-pengcheng.md - 新增：OneVL开源模型信息，更新关系网络
- 导航更新：
  - index.md - 新增2个页面，总数更新为22
  - log.md - 追加本条目
- 来源：memory/2026-08-10.md（cron任务自动记录：汽车AI应用每日动态）
- 备注：今日无robert直接对话，仅cron任务自动执行

## [2026-08-09 22:00] ingest | 2026-08-09 知识库整理
- 新建实体页面：
  - entities/xpeng.md - 小鹏汽车：AI原生定位，GX/MONA L03产品矩阵
  - entities/nio.md - 蔚来：第4000座换电站+第五代换电站投运
  - entities/volkswagen.md - 大众：ID.ERA5X首款CMP平台+CEA架构
  - entities/catl.md - 宁德时代：61.8亿中期分红，市占率39.9%
  - entities/nissan.md - 日产：研发周期50→37个月缩短40%
- 新建概念页面：
  - concepts/nev-battery-swap.md - 换电模式：蔚来4000座+1.2亿次换电
  - concepts/humanoid-robot-industry.md - 人形机器人产业：宇树IPO 610亿市值
  - concepts/automotive-rd-speed.md - 汽车研发周期：中国18-24个月vs传统50个月
- 更新现有页面：
  - entities/leapmotor.md - A10 135天破10万台纪录，激光雷达打入8万元时代
  - concepts/l3-mandatory-standard.md - 实施日期确认：2027年7月1日
- 导航更新：
  - index.md - 新增8个页面，总数更新为20
  - log.md - 追加本条目
- 来源：
  - daily-news/2026-08-09-gasgoo-evening.md
  - memory/2026-08-09.md（研判验证周回顾）
  - auto-industry/forecast-tracker.md（研判7验证）
- 备注：今日有活跃对话（研判验证周回顾），cron任务整理知识库
## [2026-08-18 22:00] ingest | 2026-08-18 robert深度对话：AI Box批判/理想AI布局/高通智驾/元戎启行/英伟达VLA/长安腾讯合作

### 新建页面（3个）
- entities/yuanrong-qixing.md - 元戎启行：VLA量产突破，高通双平台，零跑A10合作
- concepts/ai-box-software-first.md - AI Box行业"本末倒置"批判
- concepts/chinese-oem-ai-methodology.md - 中国车企AI方法论：体验定义→Agent设计→全栈自研→快速迭代

### 更新页面（5个）
- entities/li-auto.md - 新增MindVLA-o1模型、Livis OS、组织架构调整（具身工程/交互/行为三个部门）、Q1亏损23亿+943亿现金储备
- entities/changan.md - 新增长安×腾讯「AI火箭班」34人FDE团队、7大业务场景、WorkBuddy/CodeBuddy
- concepts/autonomous-driving-chips.md - 新增高通SA8650/SA8797详细对比、高通转型目的（舱驾一体差异化路线）
- concepts/vla-world-model.md - 新增英伟达Alpamayo 2 Super：34B参数、LingoQA 79.2、云端教师模型判断
- concepts/ai-in-automotive-rd.md - 新增长安×腾讯FDE合作模式、中国车企AI方法论

### 来源
- memory/2026-08-18.md（robert深度对话）

### 备注
- 今日robert进行了深度对话，核心基调：批判硬件思维，强调软件体验驱动的AI落地路径

## [2026-08-17 22:00] ingest | 2026-08-14~17 盖世汽车日报整合
### 新建页面（4个）
- entities/seres.md - 赛力斯：AI重构引擎，97万智驾用户，赛豆科技/AIVA品牌
- entities/changan.md - 长安汽车：启源Q05 10万台，启境GX7鸿蒙座舱6
- concepts/battery-white-box.md - 动力电池白盒模式：车企重构零部件定义权
- concepts/800v-platform.md - 800V高压平台已成主流，比亚迪1000V领先

### 更新页面（9个）
- entities/leapmotor.md - 7月交付101,267辆首破10万，新势力格局断层
- entities/xiaomi-pengcheng.md - 澎程系列正式发布，N70/N90价格，北京单店小订近200台
- entities/nio.md - ES9 50万级纯电冠军73天2万台，国资接手换电资产
- entities/byd.md - 海狮08预售价22.98万起，大唐EV 1000V+二代刀片，智驾保有量352万辆
- entities/zunjie.md - V680/V800正式售价，1小时大定2115台，23天预售破万
- entities/aistaland.md - GX7首发鸿蒙座舱6，主销30-35万元
- entities/saic-gm.md - 续约细节补充，股东资源倾斜
- entities/volkswagen.md - 一汽-大众双终身质保，燃油车服务升级自救
- concepts/l3-mandatory-standard.md - 标准正式发布，车企安全档案制度，A股智驾板块涨停
- concepts/nev-penetration-60-percent.md - 7月64.5%新数据，K型分化加速
- concepts/global-battery-market-2026.md - 三星SDI全资控股通用电池工厂，亿纬锂能涨价

### 来源
- daily-news/2026-08-14-gasgoo-evening.md
- daily-news/2026-08-15-gasgoo-evening.md
- daily-news/2026-08-17-gasgoo-evening.md

### 备注
- 今日robert无直接对话，仅cron任务自动执行
- 本周核心看点：新能源渗透率64.5%新高、零跑首破10万辆、小米澎程系列发布、L3国标正式发布

## [2026-08-19 22:00] ingest | 2026-08-18 盖世汽车晚报 + 2026-08-19 cron任务汇总

### 新建页面（2个）
- entities/geely.md - 吉利汽车：管理层变更（李书福→安聪慧），H1收入1736亿+46%利润，停止研发燃油动力总成，出口158%增长
- entities/xiaomi-auto.md - 小米汽车：SU7累计交付50万台（28.5个月），产品矩阵+智驾数据优势

### 更新页面（5个）
- concepts/nev-penetration-60-percent.md - 新增7月终端销量63.4%数据点、车型TOP20结构特征（燃油车仅剩5席）
- concepts/humanoid-robot-industry.md - 宇树科技8月19日上市确认，新增"超人"人形机器人视频里程碑
- concepts/autonomous-driving-chips.md - 新增2026 H1城市NOA装机量排行（华为32.3万居首，Momenta第二，元戎启行6月冲至第三）
- entities/xiaomi-pengcheng.md - 新增母公司SU7 50万台交付关联数据
- entities/geely.md - 新建

### 来源
- raw/articles/2026-08-19-gasgoo-evening.md（源自2026-08-18-gasgoo-evening.md）
- memory/2026-08-19.md（cron任务汇总）

### 备注
- 今日robert无直接对话，8个cron任务全部成功执行
- 核心看点：吉利管理层交接（创始人→职业经理人）、小米SU7 50万台里程碑、城市NOA方案商格局首次披露

## [2026-09-09 22:10] ingest | 2026-09-09 cron任务汇总（8月战报+欧洲车企+舱驾融合）

### 新建页面（12个）
- entities/renault.md - 雷诺：H1扭亏（净利7.05亿€+9.5%营收），欧洲电气化52%，Dacia Spring二代，混动长期生态
- entities/mercedes-benz.md - 奔驰：MB.EA首款量产车纯电GLC，中国定义/全球输出，Momenta纯视觉
- entities/bmw.md - 宝马：聂科维接任，iX3订单近10万，与Momenta共研R7世界模型
- entities/horizon-robotics.md - 地平线：征程1500万量产，星空6（5nm舱驾融合650TOPS），酷睿程白盒
- entities/huawei-auto.md - 华为汽车生态：乾崑ADS 5四激光+XMC底盘，生态版图（阿维塔/奕境/问界/尊界）
- entities/momenta.md - Momenta：城市NOA装机第二，宝马/奔驰双豪华客户，中国智驾反向输出
- entities/chery.md - 奇瑞：出口王，8月28万/出口19.7万（+52.1%）
- entities/tesla.md - 特斯拉：Cybercab发布（20万/无方向盘），NHTSA调查，Robotaxi
- concepts/cabin-drive-integration.md - 舱驾融合：降本驱动（利润率3.2%十年新低），星空6 vs SA8797，CAGR 36%
- concepts/cockpit-llm.md - 座舱大模型：DeepSeek 45.2%居首，自研vs外采分水岭，Agent=可信执行
- concepts/chinese-oem-export.md - 中国车企出海：三大模式（本地化/轻资产/新兴市场），8月双18万+格局
- comparisons/2026-08-china-sales-battle.md - 8月销量战报：渗透率65.8%，零跑10.3万断层，增程-19.3%

### 更新页面（14个）
- entities/byd.md - 8月44.03万（+17.8%）连续63个月销冠，海外115.8万超2025全年，方程豹4.2万
- entities/geely.md - 8月27.02万，Q2毛利率18.4%/单车收入12.6万，GTC 2026超级Eva
- entities/leapmotor.md - 8月103,129辆连续两月破10万、新势力唯一盈利，9/16世界模型发布会
- entities/xpeng.md - 8月3.91万，G9L首搭第二代VLA
- entities/li-auto.md - 8月3.77万（+32%），自研电池澄清（PACK自制+电芯代工），新MEGA自研5C
- entities/nio.md - 8月3.58万，乐道仅8,810辆，蔚来能源×云南交投5对高速换电站
- entities/xiaomi-auto.md - 累计破80万辆，龙甲电池+中创新航合作
- entities/xiaomi-pengcheng.md - 9/7正式上市20.99-29.99万，逆势重定价增程
- entities/volkswagen.md - 史上最大重组（裁5万/产能900万），SSP转多能源，奥斯纳布吕克转国防，与众08
- entities/changan.md - 8月新能源~10.5万，阿维塔T09定名（乾崑ADS 5四激光+XMC底盘）
- concepts/nev-penetration-60-percent.md - 8月渗透率65.8%新高数据点
- concepts/autonomous-driving-chips.md - 星空6（650TOPS）/SA8797（640TOPS必选项）/龍鹰二号，征程1500万
- concepts/range-extender-trend.md - 增程收缩（1-8月-19.3%），澎程重定价，修正判断
- concepts/l3-mandatory-standard.md - L3硬件预埋启动（舱内激光雷达/无方向盘测试）

### 导航更新
- index.md - 新增12页，总数31→43
- log.md - 追加本条目

### 来源
- memory/2026-09-09.md（8个cron任务汇总）
- daily-news/2026-09-09-gasgoo-evening.md

### 备注
- 今日robert无直接对话，全自动化整理
- ⚠️ **发现结构问题**：index/log自8-19后未更新，但daily-news已有8-20~9-08共约15份日报未被整理入库；另 ~/wiki（/home/admin/wiki）出现一个今天新建的空的daily-news目录，疑似某次cron误建，已忽略（真实wiki在 /home/admin/.openclaw/workspace/wiki）
- 建议：安排一次补录（8-20~9-08日报）或调整cron路径配置
- 核心看点：大众战略转向多能源+工厂转军工、增程赛道收缩、舱驾融合降本逻辑、雷诺扭亏、中国出海双引擎
- 补充：entities/stellantis.md（零跑出海合作方）、entities/qualcomm-auto.md（SA8797舱驾融合）—— 消解断链；index总数修正为48

## [2026-09-16 22:00] ingest | 9月11日-16日每日日报整合

### 新建页面（2个）
- entities/volvo.md - 沃尔沃：Q2在华暴跌35%换帅保价，2027年起独家经销领克欧洲
- concepts/fifteen-five-plan.md - 十五五规划：2030年NEV乘用车70%/商用车40%，首提自动驾驶安全正向基准

### 更新页面（19个）

#### 实体（11个）
- entities/li-auto.md - 核心重大更新：i6停售清库存/i9发布（40万级纯电旗舰，首发四项自研）/26.5亿入股欣旺达成第二大股东/自研电池覆盖全系/马赫M100（2560TOPS）+四激光雷达
- entities/leapmotor.md - 1-8月累计42.88万辆新势力登顶，格局从「蔚小理」颠覆为「零小理米」；零跑断层领跑
- entities/xiaomi-pengcheng.md - 9/7开售4分钟锁单破万；母品牌SU7累计破80万辆
- entities/seres.md - 华为合作调整：「赛力斯主导、华为赋能」轻资产模式，智选车生态进入2.0阶段
- entities/xpeng.md - XCoT可执行思维链技术报告发布（物理AI突破）；机器人业务独立融资9亿美元
- entities/tesla.md - Cybercab奥斯汀正式运营（vs Waymo 1000辆/14城）；Model Y高性能版36.9万；第36周中国9,800辆
- entities/huawei-auto.md - 智界RX获L3路测牌照（38传感器/7大场景测试）；华为生态切入换电（奕境预研换电）；赛力斯合作调整详析
- entities/catl.md - 收购重庆耀宁（吉利18GWh未建成工厂）；股价承压：车企「去宁德化」加速（A股回调35%/H股38%）；8月电池产量237GWh+69.8%
- entities/geely.md - 重庆耀宁出售给宁德：自研电池+采购宁德的复杂信号；银河战舰700预售19.98万起（6C电池）；领克欧洲由沃尔沃独家经销（2027年起）
- entities/byd.md - 马来西亚建厂搁置（改本地合作）；首款人形机器人「小迪」首秀
- entities/volkswagen.md - 裁员成本或达160亿€（含关厂+5万岗位），大众进入生存紧急状态

#### 概念（7个）
- concepts/nev-penetration-60-percent.md - 纯电占比45.3%逼近50%；8月中汽协口径60.6%；TOP10无极车；燃油车同比-40%/-45%
- concepts/vla-world-model.md - 新增小鹏XCoT报告，VLA从感知-决策-执行向感知-执行统一架构演进
- concepts/l3-mandatory-standard.md - 智界RX L3路测牌照落地（首例）；十五五规划首提自动驾驶安全正向基准
- concepts/battery-white-box.md - 理想全系自研电池覆盖；吉利重庆耀宁出售形成「卖厂+采购」复杂信号
- concepts/nev-battery-swap.md - 华为生态首次涉足换电（奕境接入宁德巧克力）；宁德2000+座覆盖180城
- concepts/global-battery-market-2026.md - 8月电池237GWh；电气化供应商1-7月装机排行（宁德42.4%+弗迪23.0%=65.4%）；车企利润vs电池厂矛盾尖锐化
- comparisons/2026-08-china-sales-battle.md - 新增第36周销量速览；8月燃油车结构崩溃数据（54万辆/-40%）

### 导航更新
- index.md - 新增2页，总数48→50
- log.md - 追加本条目

### 来源
- daily-news/2026-09-11-gasgoo-evening.md
- daily-news/2026-09-13-gasgoo-evening.md
- daily-news/2026-09-16-gasgoo-evening.md

### 备注
- 今日robert无直接对话，全自动化整理
- 这期内容量大且关键：理想i9发布是Q4纯电旗舰基准、华为L3路测是行业首个、车企「去宁德化」进入加速期
## [2026-09-19 22:00] ingest | 2026-09-19 每日知识整理（cron自动化）

### 新建页面（2个）
- concepts/ai-engineering-2026.md - 2026年汽车行业AI工程化：AI从概念验证到全链条价值兑现，光庭SDW/东软AIOS/长安AI全链路三路径并行
- [index补录] solid-state-battery.md - 比亚迪硫化物全固态2027上车确认，固态电池技术路线竞争格局更新

### 更新页面（18个）

#### 实体（12个）
- entities/byd.md - 海狮08上市(22.99-27.99万/天神之眼5.0)，固态电池2027上车确认(硫化物400Wh/kg/1218km)，H1海外79.2万辆
- entities/leapmotor.md - CTC 3.0取消独立蓄电池+48V低压架构，8月单车净利仅583元
- entities/geely.md - 极氪IPO不足600天私有化退市正式并入吉利，品牌缩减至4个
- entities/xpeng.md - Infini-VLA长时序架构(前30秒记忆+推演6秒+响应提速300%)，G9L首发
- entities/volkswagen.md - Future Plan 2030裁约10万+4座EV工厂停产，ID.Polo售罄，ID.3 GTI发布
- entities/renault.md - 巴西合资EX5 EM-i首车下线(签约不到一年)，IAA新Trafic Van E-Tech双电池
- entities/tesla.md - NHTSA正式立案调查Cybercab，FSD滥用面临145亿美元诉讼
- entities/bmw.md - Neue Klasse iX3大获成功验证中国智驾+欧洲底盘模式
- entities/mercedes-benz.md - GLA EV发布(MMA/800V/657km)，电动C-Class匈牙利投产
- entities/horizon-robotics.md - 星空Starry 6P(5nm舱驾融合)定位更新，与SA8797正面竞争
- entities/qualcomm-auto.md - SA8797算力翻倍至1280TOPS，零跑D19首发双芯2560TOPS
- entities/seres.md - 问界品牌价值34.5亿美元，一级供应商压缩至100家以内

#### 概念（6个）
- concepts/cabin-drive-integration.md - SA8797 1280TOPS格局更新，零跑D19双芯方案
- concepts/chinese-oem-ai-methodology.md - 2026年9月AI工程化价值兑现阶段
- concepts/chinese-oem-export.md - H1出海提速，雷诺巴西合资首车下线
- concepts/solid-state-battery.md - 比亚迪硫化物路线2027上车确认
- concepts/vla-world-model.md - Infini-VLA长时序架构，VLA技术路线更新
- concepts/ai-engineering-2026.md - （新建）2026汽车AI工程化

### 导航更新
- index.md - 54页(+2)，更新日期至2026-09-19，新增ai-engineering-2026/solid-state-battery条目
- 全部18个页面摘要同步更新

### 来源
- memory/2026-09-19.md（7个cron任务汇总）
- raw/articles/2026-09-19-daily-digest.md（新建）

### 核心洞察
- **AI工程化不可逆**：光庭SDW、东软AIOS、长安AI全链路、豆包座舱助手——四个独立信源指向同一趋势
- **SA8797算力翻倍**：1280TOPS重新定义舱驾一体芯片竞争格局，地平线星空6P的650TOPS面临算力代差
- **零跑悖论深化**：10.3万/月规模+唯一盈利但单车净利仅583元——scale economy仍未兑现利润
- **欧洲产能结构性危机**：大众裁10万+4厂停产 vs BEV渗透率22%，EV需求集中在入门级不足以支撑过剩产能
- **雷诺巴西速度**：签约不到一年首车下线，中国技术输出拉美模式验证

### 备注
- 今日robert无直接对话，cron任务自动化整理
- 覆盖7个独立cron输出源

## [2026-09-20 22:00] ingest | 2026-09-20 每日信息整理（7个cron任务+盖世晚报）

### 新建页面（0个）
（今日全部为增量更新）

### 更新页面（10个）

#### 实体（7个）
- entities/catl.md - 全固态电池至少还需五年，看好钠电和凝聚态，与比亚迪硫化物路线形成路线分歧
- entities/xpeng.md - 技术出海升级，从大众单一客户→多车企授权EE架构/座舱/图灵芯片
- entities/li-auto.md - 启动外供：马赫芯片/碳化硅模组/增程器独立运营
- entities/volkswagen.md - 裁员扩至10万+4座EV工厂停产；FAW-VW ID. AURA T6开启预售
- entities/changan.md - 泰达论坛：张晓宇给出L3 2027量产/L4 2028商业化的明确时间表
- entities/tesla.md - Optimus宁波审厂，拓普集团确认合作
- entities/renault.md - IAA Trafic Van E-Tech：首款SDV纯电商用车（CarOS+800V+V2L/V2G），futuREady战略

#### 概念（3个）
- concepts/cockpit-llm.md - 豆包座舱助手首发荣威家越07，具身交互+AI Planner直驱实体
- concepts/vla-world-model.md - CVPR 2026焦点转向"理解与预测世界"，VLA+世界模型深度融合
- concepts/humanoid-robot-industry.md - 特斯拉Optimus宁波审厂，拓普确认合作

### 导航更新
- index.md - 54页不变，更新日期至2026-09-20
- log.md - 追加本条目

### 来源
- raw/articles/2026-09-20-daily-digest.md（新建）
- memory/2026-09-20.md（7个cron任务汇总）

### 核心洞察
- **宁德唱空全固态**：权威发声至少还需五年，聚焦钠电和凝聚态——与比亚迪2027承诺形成路线对立
- **小鹏/理想双双转型技术供应商**：小鹏对外授权EE/座舱/芯片，理想外供马赫芯片/碳化硅/增程器——中国新势力从"造车"转向"技术输出"
- **大众生存重组确认**：裁员10万+4厂停产，欧洲22% BEV渗透率下的产能结构矛盾无解
- **长安L3/L4时间表**：央企首个明确时间表，可信度高于新势力
- **特斯拉Optimus审厂**：机器人量产转入供应商阶段，拓普切入机器人供应链
- **CVPR 2026信号**：VLA+世界模型融合成为量产核心方向，从"识别"到"理解与预测"

### 备注
- 今日robert无直接对话，cron任务自动化整理
- 涵盖7个独立cron输出源
- ✅ li-auto.md 外供部分修复上次编辑的格式问题



## 2026-09-21 索引重建
- 问题：index.md 仅注册 54 页，实际 248 页，64+ 实体页面为"暗页面"
- 修复：脚本扫描全部 frontmatter，重建 index.md
- 结果：248 页全部收录（entities 93 / concepts 140 / comparisons 4 / auto-industry 10 / european-automakers 1）
- 新增分类：车企按国别拆分（中/欧/美/日/韩），供应商/方案商独立成类，芯片厂商单列
- 新增摘要：每页自动提取首行内容作为描述


## 2026-09-21 每日整理（22:00）

### 新建（2）
- raw/articles/2026-09-21-daily-digest.md - 今日资讯汇总（奔驰命名重组/EQ退场、雷诺Twingo与Niagara、座舱分层模型）
- concepts/cockpit-model-tiering.md - 座舱模型分层架构（奔驰Momentum 1+云 / Jetta M6 3模型 / 特斯拉语音 2模型）

### 更新（3）
- entities/mercedes-benz.md - 【合并重复页】并入旧mercedes.md全部历史内容；新增9月命名重组（GLB不再叫EQB、GLC EV汉诺威亮相）、Momentum分层座舱
- entities/renault.md - 新增Niagara皮卡阿根廷全球首发、Provost开发周期红线、Twingo E-Tech参数补全
- entities/li-auto.md - 新增Mind GPT通过国家级备案（响应提速5倍、投入180亿量级）
- concepts/cockpit-llm.md - 新增Mind GPT备案、座舱模型分层架构主流化

### 归档（1）
- entities/mercedes.md → _archive/mercedes.md（与mercedes-benz.md重复，合并后归档）
  - 4处 [[mercedes]] 引用重定向为 [[mercedes-benz]]（bba-ev-ranking-2026 / cockpit-model-tiering / eu-ev-market-2026 / european-automakers/2026-06-movement）

### 导航更新
- index.md - 删除重复mercedes条目，更新mercedes-benz摘要；新增cockpit-model-tiering；技术分类80→81、欧洲车企10→9
- 索引完整性校验：comm 输出为空（248页全部注册，缺失0）
- Total pages 248（entities 92 / concepts 141 / comparisons 4 / auto-industry 10 / european-automakers 1）

### 核心洞察
- **EQ品牌事实退场**：GLB不再叫EQB、GLC EV汉诺威亮相——奔驰电动线全面回归主品牌命名，EQ后缀作为品牌资产被证伪
- **座舱模型分层主流化**：奔驰Momentum(1+云)/Jetta M6(3)/特斯拉语音(2)同时采用分层架构，成为跨阵营架构收敛；理想Mind GPT首个车企自研大模型通过国家备案
- **雷诺双线**：欧洲平价电动（Twingo 263km/<2万欧）+ 拉美第二主场（Niagara皮卡阿根廷首发）；Provost明确2年开发周期红线
- **数据质量修复**：发现并合并重复实体页mercedes(.md/-benz.md)

### 备注
- 今日以基础设施工作为主（Wiki索引重建确认、GitHub备份核验），行业资讯为凌晨dreaming对09-20日报的二次摄取

## 2026-09-22 每日整理（22:00）

### 新建（5）
- raw/articles/2026-09-22-daily-digest.md - 今日资讯汇总（AI Box形态/大众跌出Euro Stoxx/泰达经销商毛利/日产美国增产/特斯拉Optimus审厂）
- concepts/ai-box-independent-compute.md - 独立AI算力需求与AI Box形态演进（内存带宽隔离视角、三形态、出海合规逻辑）
- concepts/euro-stoxx-50-exit.md - 欧洲车企被剔除蓝筹指数（大众15年首次，Stellantis先例，结构性定价）
- concepts/dealer-margin-crisis.md - 经销商毛利危机与残值崩塌（泰达-21.4%口径澄清，残值=品牌资产）
- concepts/advanced-node-capacity-2027.md - 先进制程产能被AI芯片预订至2027（汽车芯片隐性风险）

### 更新（6）
- concepts/ai-box-software-first.md - 新增 [[ai-box-independent-compute]] 反向链接，补源
- entities/volkswagen.md - 新增被剔除Euro Stoxx 50、重组月度补充（再裁5万/SSP拖延/CARIZON）
- entities/nissan.md - 新增美国增产（487k→1M/2030，三班制不建新厂）、Pixo换标复活
- entities/li-auto.md - 新增芯片子公司150亿估值判断（金融工程/天花板低）
- entities/tesla.md - Optimus审厂合作方补全（拓普/三花/均胜）
- entities/renault.md - 新增IAA商用车（Trafic Van E-Tech/Master V2G）、巴西合资加码、Twingo平台外溢日产

### 导航更新
- index.md - 新增4个概念页（技术+2、市场/趋势/政策+2）；更新Total pages 248→252
- 索引完整性校验：comm 输出为空（252页全部注册，缺失0）
- Total pages 252（entities 92 / concepts 145 / comparisons 4 / auto-industry 10 / european-automakers 1）

### 核心洞察
- **独立AI算力是真需求，Box只是形态**：本质是内存带宽隔离（memory-bound）；形态演进后装Box→板载协处理器/Chiplet→单芯集成；出海窗口期可能更长（合规门槛）
- **AI Box = 用硬件换合规**：GDPR把DMS/街景定为个人数据，"数据不出车"海外是准入门槛而非加分项
- **欧洲车企连续两年被踢出蓝筹指数**（Stellantis 2025.9/大众 2026.9）：市场判定结构性而非周期性，裁员10万仅省营收3%
- **价格战代价在经销商**：新车毛利率-21.4%（vs行业利润率3.6%），残值崩塌=品牌资产归零
- **3nm/5nm产能被AI芯片预订至2027**：汽车芯片只能在剩余产能抢，与存储涨价同源
- **2026是"含模量"分水岭**：比拼工程化落地能力，全栈自研+算力储备者收割中高端
- **L3"试点非量产"冷现实**：德系收缩，有沦为鸡肋风险

### 备注
- 今日robert直接对话2轮（AI Box深度追问、行业动态批量点评）+ 7个cron报告

## 2026-09-23 每日整理（22:00）

### 新建（2）
- raw/articles/2026-09-23-daily-digest.md - 今日资讯汇总（座舱AI五级分级/存储涨价推手/Cybercab运营/欧洲车企中国技术授权）
- concepts/cockpit-ai-capability-grading.md - 座舱AI能力五级分级（中汽智能 2026-09-08 发布：规则响应→场景辅助→主动服务→自主协同→全域智能）

### 更新（4）
- entities/renault.md - 新增雷诺5（R5）改款 9/22 开启预订（£21,495 加量不加价、OTA 接入 Google Gemini）
- entities/volkswagen.md - 新增 ID. UNYX 09 轿车 9/24 首发（与 [[xiaopeng]] 联合开发、CEA 架构）
- concepts/cockpit-llm.md - 新增座舱AI能力五级分级小节 + 反向链接
- concepts/cockpit-ai-evolution.md - 未改（已在 cockpit-llm 交叉）

### 导航更新
- index.md - 技术分类新增 cockpit-ai-capability-grading；更新 Total pages 252→253
- 索引完整性校验：comm 输出为空（253页全部注册，缺失0）
- Total pages 253（entities 92 / concepts 146 / comparisons 4 / auto-industry 10 / european-automakers 1）

### 核心洞察
- **座舱AI首次有了能力坐标系**：中汽智能五级分级对标智驾 L0-L5，把"AI座舱"从营销话术拉回可评估阶梯；渗透率38.6%≠能力等级，L4自主协同仍是头部玩家专属
- **9月是 L3/L4 分水岭**：Cybercab 无方向盘运营 + 国内 L3 强制国标 2027-07-01 实施倒计时
- **舱驾一体加速器是存储涨价**：省一套 DDR 即保毛利，Q4 关注成本向定价传导
- **欧洲车企集体倒向"中国技术授权+本土化"**：大众/奔驰/宝马智驾全数押注 Momenta 或本土伙伴

### 备注
- 今日全天无 robert 直接对话，均为 cron 产出；多数 8月销量/欧洲动态已在 09-19~09-22 完成摄取，本次以去重后的净新增内容为主

## 2026-09-24 每日整理（22:00）

### 新建（4）
- raw/articles/2026-09-24-daily-digest.md - 今日资讯汇总（迪迪虾/高通8797量产/星空6+咖咖虾OS/L3牌照竞速/Faros遥测/汽车AI云市场/雷诺股价）
- entities/di-di-xia.md - 比亚迪超级智能体（通义千问+阿里生态，跨应用自动执行，首搭腾势N8L）
- entities/snapdragon-8797.md - 高通旗舰舱驾融合芯片（~700TOPS/NPU上代12倍/端侧300亿MoE，零跑D19双芯首发）
- concepts/auto-ai-cloud-market.md - 汽车AI云市场（沙利文：2025年122亿→2029年753亿，CAGR 57.5%）
- concepts/ai-productivity-verification-gap.md - AI提效的验证门禁瓶颈（Faros AI 2026：吞吐+33.7% vs 评审+441.5%/返工+861%）

### 更新（12）
- entities/starry-sky-chip.md - 补星空6正式规格（5nm/6P 650/6H 500TOPS）+ 咖咖虾OS；tags规范化
- entities/snapdragon-8775.md - （未改，由 snapdragon-8797 交叉引用）
- entities/qualcomm-auto.md - 新增SA8797量产确认（~700TOPS/端侧300亿MoE）+ 8775走量双档矩阵
- entities/renault.md - 新增巴黎车展阵容（6款首发）+ 股价一周跌8%
- entities/zhijie.md - 新增智界RX获L3路测牌照（9/16）+ 预售24h L3架构版占比>90%
- entities/byd.md - 新增泰国工厂第10万辆下线 + 迪迪虾发布
- entities/nio.md - 新增ES9第3万台交付（119天）
- entities/bmw.md - 新增CEO反对欧盟对华加税
- entities/catl.md - 新增宁德时代×五菱城配电池（1万次循环）
- concepts/l3-mass-production-2026.md - 新增2026年9月牌照竞速（长安首块L3专用牌照/GB 44721-2026节点）
- concepts/cockpit-llm.md - 新增比亚迪迪迪虾（生态派代表）+ 反向链接
- concepts/humanoid-robot-industry.md - 新增车企集体造人（14家，小鹏/长安/奇瑞）
- concepts/eu-ev-market-2026.md - 新增H1 2026 BEV 160.8万辆 + 8月EV+40%/份额38%

### 导航更新
- index.md - 芯片厂商+1（snapdragon-8797）、产品/平台+1（di-di-xia）、市场/趋势/政策+1（auto-ai-cloud-market）、工具/工程+1（ai-productivity-verification-gap）；更新 Total pages 253→257
- 索引完整性校验：comm 输出为空（257页全部注册，缺失0）
- Total pages 257（entities 94 / concepts 148 / comparisons 4 / auto-industry 10 / european-automakers 1）

### 核心洞察
- **AI提效的真实分水岭在「工程门禁」**：Faros 2.2万开发者遥测显示生成速度已不是瓶颈，评审/测试/仿真/覆盖率能否跟上才是；不同步重造CI/CD门禁=埋雷
- **L3的最后一公里是法律与成本，不是技术**：9月道交法修订草案补齐责任框架，但2027-07-01强制国标前不会大规模放开，「L3架构版」话术需打折
- **舱驾一体是2026确定性最高的架构变革**：驱动力是存储涨价+降本，8797/星空6双线量产后2027年15-25万主流市场快速普及
- **供应商把「卖芯片」升级为「卖平台」**：地平线出咖咖虾OS、英伟达出Alpamayo、华为出乾崑OS，用生态守城
- **雷诺产品与资本背离**：巴黎车展6款首发 vs 股价一周-8%，资本市场只认利润率与欧洲EV需求
- **车企集体「造人」是被主业逼出来的转身**：利润率仅3.6%、利润-20.4%背景下，人形机器人是第二曲线也是无奈之举

### 备注
- 今日全天无 robert 直接对话，均为 cron 产出（6个日报/简报）；本次以去重后的净新增内容为主

## 2026-09-25 每日整理（22:00）

### 新建（3）
- raw/articles/2026-09-25-daily-digest.md - 今日资讯汇总（座舱AI壁垒对话 + 欧洲车企/雷诺/汽车AI工程/汽车AI全景/盖世晚报）
- concepts/cockpit-ai-barrier-layering.md - 座舱AI壁垒分层（核心：功能层零壁垒，约束层才是护城河）
- entities/dicore.md - 比亚迪座舱OS中间件（迪迪虾执行层，主机厂独占的中等壁垒）

### 更新（10）
- entities/byd.md - 新增 DiCore 座舱OS中间件曝光（9/25）+ 璇玑架构2.0
- concepts/cockpit-llm.md - 新增「功能层 vs 约束层」壁垒讨论 + 反向链接
- entities/volkswagen.md - 新增中国智驾与地平线升级（CARIZON 60%/C7H SoC/GAIA世界模型）+ CEA/SSP架构分治
- entities/mercedes-benz.md - 新增纯电产品矩阵（CLA EV/GLB EV/纯电GLC）+ Momenta 2017最早押注
- entities/bmw.md - 新增 iX3 中国9/8申报完成、11月交付、+108mm、座舱三方案
- entities/renault.md - 新增6亿欧元加码西班牙、8 Gordini概念车、Dacia Spring回迁
- concepts/l3-mandatory-standard.md - 新增关键细节「L2车无法OTA升L3」
- concepts/generative-engine-optimization.md - 新增渗透数据（88.6%用AI搜索/44%核心工具）
- concepts/ai-software-engineering.md - 新增工业级AI工具（微软零样本97%/宝马提速12倍/西门子100+Agent/凯捷89%）
- entities/volcengine.md - 新增豆包上车超700万辆（50+品牌145款车型）
- concepts/physical-ai.md - 新增技术主线转移（端到端→物理AI基座模型，CVPR 2026首设研讨会）

### 导航更新
- index.md - 产品/平台+1（dicore）、技术+1（cockpit-ai-barrier-layering）；更新 Total pages 257→259
- 索引完整性校验：comm 输出为空（259页全部注册，缺失0）
- Total pages 259（entities 95 / concepts 149 / comparisons 4 / auto-industry 10 / european-automakers 1）

### 核心洞察
- **座舱AI壁垒在约束层不在功能层**：Agent/编排/主动服务注定被复制，护城河在 OS中间件/跨域隔离/车规级AI安全/端侧效率/确定性编排。功能层是公开战场，约束层才是护城河。
- **DiCore 是比亚迪真正的护城河**，不是迪迪虾 Agent（千问+公开协议，零壁垒）。
- **座舱数据没有网络效应**（与智驾数据相反），唯一例外是跨设备数据（小米人车家/华为1+8+N）。
- **中立供应商的座舱困境**：往上没壁垒、往下没地盘；国外主机厂生意壁垒=合规+本地化（准入壁垒）。
- **L2 无法 OTA 升 L3** 是关键政策细节，影响存量车主与二手车逻辑。
- **大众架构分治**：东半球CEA（小鹏）/西半球SSP（Rivian），中国智驾白盒授权地平线。
- **AI 工程化跨过 demo 门槛**：自动标注零样本97%、测试分析提速12倍——但天花板是功能安全合规。

### 备注
- 今日有一次 robert 直接对话（15:10 座舱AI壁垒），为核心沉淀；其余为 6 个 cron 日报

## 2026-09-26 每日整理（22:00）

### 新建（6）
- entities/snapdragon-8787.md - 高通舱驾融合主流档芯片（15-25万价位带），对标「8295座舱+ADAS双芯」，与8797/8775构成三档矩阵
- entities/xinchi-x10.md - 芯驰科技4nm车规座舱AI芯片，80TOPS/154GB/s带宽，单芯片支持9B端侧大模型
- entities/roewe-jiayue-07.md - 上汽荣威13.78万起车型，「全额包揽用户Token成本」——判断为营销而非商业模式
- entities/geely-super-eva.md - 吉利座舱AI Agent「超级Eva」，基座阶跃星辰Step 3.5 Flash，首发极氪8X
- concepts/swe-agent-paradigm.md - SWE-Agent范式：交付周期-42%、单测-68%、缺陷逃逸-37%，但无自省闭环幻觉率42%
- concepts/51sim-simone-4.md - 51Sim SimOne 4.0智驾仿真平台：4DGS重建+生成式世界模型，一致性92%

### 更新（18）
- entities/byd.md - 8月海外18.95万辆(+134%)/占比43%、匈牙利11-12月组装、补能2万→9万座闪充站
- entities/nio.md - Q2营收321.37亿(+69.1%)、净亏5.28亿、第4000座换电站
- entities/nio-shenji.md - 神玑NX9031已交付超25万颗
- entities/chery.md - 全固态2027上车验证、犀牛固液混合2026Q4装车
- entities/geely.md - 8月极氪36981/领克17027(-37%)、2026目标345万辆、银河E5 9.78万起
- entities/bmw.md - iX3中国版沈阳产/CLTC破900km、Momenta L2++ 2027底覆盖12款、iX5 Hydrogen 2028
- entities/volkswagen.md - SSP 2027降本20%/中国专属版提前一年、Cariad裁员1600、年底减员19000
- entities/mercedes-benz.md - Momenta R6年内扩至9款车型、座舱接入豆包
- entities/jaguar-land-rover.md - 裁员4000+网络攻击停摆、Range Rover Electric再推迟
- entities/stellantis.md - 2028马德里工厂、B10将挂欧宝标
- entities/xpeng.md - 第二代VLA砍语言转译层(20亿/1亿clips)、图灵750TOPS获大众定点、跳过L3直取L4
- entities/renault.md - 西班牙6亿欧元/三菱Eclipse Cross EV/巴西EX5下线/研发周期3年→20个月
- entities/horizon-robotics.md - 星空6「城堡」物理隔离、首发客户iCAR
- entities/qualcomm-auto.md - 新增骁龙8787（三档矩阵）
- concepts/world-model.md - 世界模型「祛魅」（WorldEngine/ResWorld、VLA+世界模型融合期）
- concepts/advanced-node-capacity-2027.md - 英伟达Thor算力跳票2000→700TOPS
- concepts/cockpit-model-tiering.md - 端侧常驻模型压缩至3B以内、座舱市场1828亿
- concepts/auto-ai-cloud-market.md - 数据闭环市场2026预计450亿美元(+18%)、云端算力占40%
- concepts/ai-token-economics.md - 荣威家越07「免费Token」营销样本

### 素材
- raw/articles/2026-09-26-daily-digest.md - 今日7个cron日报汇总
- daily-news/2026-09-26-gasgoo-evening.md - 盖世汽车晚报（补录）

### 导航更新
- index.md - 芯片厂商+2（snapdragon-8787、xinchi-x10）、产品/平台+2（geely-super-eva、roewe-jiayue-07）、工具/工程+2（swe-agent-paradigm、51sim-simone-4）；更新 Total pages 259→265
- 索引完整性校验：comm 输出为空（265页全部注册，缺失0）
- Total pages 265（entities 99 / concepts 151 / comparisons 4 / auto-industry 10 / european-automakers 1）

### 核心洞察
- **世界模型「祛魅」**：从端到端万能兜售 → 定向补corner case的训练工具，可解释认知+可验证几何重新引入系统
- **英伟达Thor跳票（2000→700TOPS）**成供应链最大不确定性，倒逼蔚小理集体自研「去英伟达化」
- **舱驾融合芯片是2026利润保卫战核心**：行业销售利润率3.2%、单车净利<1万，单芯片是最直接的省钱方案（地平线星空6、高通8787）
- **座舱Agent竞争从「会聊」转向「能干活」**，壁垒在底层车载基础软件
- **中国技术反向输出不可逆**：雷诺研发周期3年→20个月是标志性案例
- **警惕「免费Token」打法**（荣威家越07）：营销而非商业模式

### 备注
- 今日全天无 robert 直接对话，均为 cron 产出；本次以去重后的净新增内容为主

## [2026-09-27 22:00] ingest | 2026-09-27 每日信息整理（8个cron日报+研判周回顾）

### 新建页面（4个）
- entities/wudang-c1296.md - 黑芝麻武当C1296：本土首个量产舱驾一体方案，与地平线星空6P、高通8797同台
- concepts/vehicle-computing-agent.md - 计算智能体（汽车）：吉利WNEVC定调「汽车→计算智能体」，核心是「主动性」
- concepts/battery-electrode-stacking.md - 叠片加速替代卷绕：理想/小鹏/小米导入，电池制造工艺层结构性升级
- concepts/siemens-xcelerator-ai-agents.md - 西门子Xcelerator上线100+ AI Agent，工业软件侧AI工程化代表

### 更新页面（5个）
- entities/volvo.md - 2027年1月起沃尔沃成领克欧洲独家经销商（轻资产借渠道）
- entities/zeekr.md - 极氪9X 9/29上市45.59万起/13分钟大定破万；吉利高端「三个9」矩阵
- entities/leapmotor.md - D19双8797全球首发（~1280TOPS）；世界模型4.0接管率为头部1/3
- entities/wenjie.md - 问界新M8 9/30预售（全系L3架构）
- entities/blacksesame.md - 补录武当C1296（本土首个量产舱驾一体）
- concepts/cockpit-driving-fusion.md - 新增2026 Q3「爆发」表（星空6P/8797/武当C1296），诱因是钱（利润率1.5%）

### 素材
- raw/articles/2026-09-27-daily-digest.md - 今日8个cron日报+盖世晚报汇总

### 导航更新
- index.md - 芯片厂商+1（wudang-c1296）、技术+3（vehicle-computing-agent、battery-electrode-stacking、siemens-xcelerator-ai-agents）；更新 Total pages 265→269
- 索引完整性校验：comm 输出为空（269页全部注册，缺失0）
- Total pages 269（entities 100 / concepts 154 / comparisons 4 / auto-industry 10 / european-automakers 1）

### 核心洞察
- **整车利润率跌至1.5%（十年新低）**：舱驾融合从"技术选择"变"利润保卫战刚需"（星空6P单车省1500–4000元、零跑D19双8797）
- **计算智能体=叙事框架升级**：壁垒不在功能而在约束——Agent层可复制，中间件（碰CAN/座椅ECU）与芯片不可借
- **叠片替代卷绕**：继"半固态/全固态"之后的电池隐性战线，高端+超快充先渗透
- **工业软件侧AI工程化**：西门子100+ Agent量化ROI（↓30%/↑5倍/↑66%），与车企自研侧形成两股力量
- **沃尔沃渠道变现**：领克借沃尔沃欧洲网络轻资产出海，关键变量是渠道利润分配与品牌调性冲突
- **研判6机制盲点**：碳酸锂跌破13.5万方向对，但SMM库存口径调整后翻倍——"需求分流"叙事曾掩盖供给过剩；判断准则累计7条

## [2026-09-28 22:00] ingest | 2026-09-28 每日信息整理（8个cron日报+盖世晚报）

### 新建页面（3个）
- concepts/geely-nio-swap-alliance.md - 吉利×蔚来换电联盟：资本互持（易易互联100%股权+6.4亿→蔚来能源30%；蔚来反向持股浩瀚能源10%）+统一C端换电标准
- entities/shenxingzhe-8.md - 神行者8：奇瑞×捷豹路虎联合打造，30.99-45.99万，华为乾崑ADS5+896线激光雷达
- comparisons/battery-swap-vs-ultra-fast-charging.md - 补能路线之争：换电联盟 vs 超充阵营（对比维度+破局点+观察指标）

### 更新页面（25个）
- entities/zhijie.md - 智界RX上市（25.98-38.98万，L3架构版31.98万起，浙赛1:43.210纪录）；鸿蒙智行累计交付155万辆
- entities/nio.md - 8月3.58万首次同时被小鹏理想超越、港股跌超5%；充换电站9410座；吉利资本互持
- entities/geely.md - 换电联盟；涪陵耀宁电池工厂让渡宁德（收缩电芯重资产）
- entities/catl.md - 接盘重庆涪陵85亿30GWh确认（市监总局9/3无条件批准）；产能利用率94.86%
- entities/deepal.md - 第100万辆下线；S07 AI激光版（豆包共创）；泰国罗勇工厂10万台/年
- entities/momenta.md - 城区NOA市占率超60%；MG07 245版11.89万下探10万级（R7世界模型）
- entities/chery.md - 8月28.01万/出口19.7万；神行者8
- entities/changan.md - 8月21.88万、出口+78.6%但国内承压
- entities/pony-ai.md - Q2收入1207万美元（+691%）；车队1975→年底3500+
- entities/li-auto.md - H1毛利率9.5%新势力最低；8月3.77万反超蔚来
- entities/xiaopeng.md - 8月3.91万首超蔚来；第二代VLA（30秒记忆+6秒推演）；图灵750TOPS下放15万级
- entities/xiaomi-auto.md - 不自造电芯（中创新航/欣旺达龙甲电池）；累计210亿芯片投入
- entities/yuanrong-qixing.md - 1亿美元C1轮；年底三款车；端到端量产车跑Robotaxi
- entities/renault.md - 巴黎车展8 Gordini概念车；巴西新增投资3.19亿欧元
- entities/horizon-robotics.md - 征程1500万颗（9/15）；31.94%市占率新口径（标注与13.6%口径差异）
- entities/wenjie.md - 赛力斯主导后首场发布会改录播
- entities/volcengine.md - 豆包座舱正式入局方案商；深蓝S07共创
- concepts/nev-battery-swap.md - 吉利×蔚来联盟格局质变；9410座
- concepts/city-noa-penetration.md - 渗透率15%→18%；下探10万级
- concepts/new-forces-landscape-2026.md - 8月「零跑独一档+3.5-4万混战区」；蔚小理铁三角瓦解
- concepts/eu-ev-market-2026.md - ACEA 8月纯电+62.7%、份额27.7%；中国品牌欧洲逼近12%
- concepts/world-model.md - 世界模型平权（零跑10万级/乾崑9.99万/小鹏VLA2代）
- concepts/l3-mandatory-standard.md - 全国仅2款L3准入；2027年7月强标是分水岭
- concepts/ai-engineering-2026.md - 零跑提效90%、东风自动化90%、江汽迈思特
- concepts/nev-penetration-60-percent.md - 9月渗透率65.7%；28款新车卡位国庆

### 素材
- raw/articles/2026-09-28-daily-digest.md - 今日8个cron日报+盖世晚报汇总

### 导航更新
- index.md - 产品/平台+1（shenxingzhe-8）、市场/趋势/政策+1（geely-nio-swap-alliance）、comparisons+1（battery-swap-vs-ultra-fast-charging）；Total pages 269→272（entities 101 / concepts 155 / comparisons 5）
- 索引完整性校验：comm 输出为空（272页全部注册，缺失0）

### 核心洞察
- **换电进入「联盟 vs 联盟」时代**：吉利×蔚来资本互持+标准共建是今日最值得跟踪的结构性事件；对标宁德巧克力换电+超充联盟，补能竞争从企业级升级到生态级
- **蔚小理铁三角正式瓦解**：8月小鹏、理想同时反超蔚来，3.5-4万/月成密集混战区；蔚来被超越本质是乐道未放量
- **智驾平权进入10万级**：城区NOA渗透率18%、Momenta市占率超60%、MG07 245版11.89万——世界模型从旗舰炫技变标配
- **技术平权快于法规平权**：全国仅2款L3准入 vs 算力下放15万级；2027年7月GB44721-2026强标才是真分水岭
- **宁德「接盘式扩张」**：85亿接吉利涪陵30GWh在建产能，产能过剩期用收购替代新建；与车企「去宁化」两极分化并存
- **渗透率65.7%含脉冲成分**：28款新车卡位国庆黄金周，Q4补贴退坡后分化才见真章

## [2026-09-29] ingest | 每日Wiki整理（8个cron日报 + 盖世晚报）
- **新建**：
  - concepts/battery-fifteen-five-plan.md - 七部门《新型电池产业"十五五"规划》（2030全固态规模化/15000次循环/PPB缺陷率/支持兼并重组）
  - raw/articles/2026-09-29-daily-digest.md - 今日cron汇总素材
  - raw/articles/2026-09-29-battery-15five-plan-nbd.md - 每经原文抓取（电池规划+国轩大众32.22亿欧+宁德减持裕能）
- **更新（13页）**：
  - concepts/geely-nio-swap-alliance.md - 蔚来能源估值160亿；吉利换电车型2027；2030万座目标
  - concepts/solid-state-battery.md - 比亚迪2027全固态定档（硫化物+硅基负极400Wh/kg/1218km原型/仰望首搭）
  - concepts/gen-2-blade-battery.md - 腾势Z9S 1100km纪录；汉EV 2026款1008km+5分钟闪充10-70%
  - concepts/lithium-price-surge-2026.md - 锂价跌破13.5万；SMM库存口径8.7→17.5万吨修正（结构性过剩属实）
  - concepts/ai-engineering-2026.md - WorkBuddy零跑90%提效；蔚来×TRAE组织级（采纳率90%/入库率19.8%）；国产PLM 42.3亿；汽车云100.9亿
  - concepts/world-model.md - 上汽大众ID.ERA 9X首搭Momenta R7（合资首次量产世界模型）
  - concepts/cockpit-llm.md - 斑马AutoOmni 2.0量产；豆包座舱700万辆/50+品牌145款
  - concepts/polestar-us-ban-2026.md - 放弃上诉全面退出美国；中资关联合规红线
  - concepts/global-battery-competition.md - 国轩×大众32.22亿欧欧洲建厂；宁德减持湖南裕能
  - entities/volkswagen.md - "2030未来计划"（裁员10万/车型砍半/产能1200→900万）；Cariad转外采；ID.ERA 9X；ID.AURA T6
  - entities/horizon-robotics.md - H1营收20.55亿；31.94% vs 英伟达29.38%；征程6H装ID.AURA T6
  - entities/momenta.md - 本田全球唯一高阶智驾供应商；城NOA市占65%；GLE长轴首搭
  - entities/renault.md - 巴黎车展6首发+4概念/周期2年；Duster Hybrid印度1.4kWh大电池强混；Rafale限量1500台
  - entities/jaguar-land-rover.md - 两年降本17亿英镑（补入9月裁4000人条目）
- **导航更新**：index.md - Concepts/市场趋势政策+1（battery-fifteen-five-plan）；Total pages 272→273（entities 101 / concepts 156 / comparisons 5 / auto-industry 10 / european-automakers 1）
- **索引完整性校验**：comm 输出为空（273页全部注册，缺失0）
- **核心洞察**：①固态电池2027装车倒计时但液态已卷到1100km，规划是"锦上添花"；②换电资本级整合（蔚来×吉利）重塑补能竞争格局；③合资品牌算法国产化（ID.ERA 9X/ID.AURA T6）标志欧洲电动化进度条由中国供应商说了算；④AI Coding进组织级平台阶段；⑤碳酸锂"方向对≠机制对"：库存口径修正揭示结构性过剩

## [2026-09-30] ingest | 每日Wiki整理（10个cron日报 + 盖世晚报）
- **新建**：
  - comparisons/2026-09-china-sales-battle.md - 9月大盘：零售224.1万（+6.3%）创9月纪录、新能源129.6万/渗透率57.8%、燃油车企利润率1.5%近十年最低、新车60+款
  - raw/articles/2026-09-30-daily-digest.md - 今日cron汇总素材（含研判周回顾要点）
- **更新（15页）**：
  - entities/byd.md - 9/28马来西亚签约（自建搁置→合作落地）；方程S/SGT 18.99万起；秦MAX首月2,787台；5个月1万座闪充站；2026海外180万/2027 250万目标
  - entities/zeekr.md - 9X出海（SEP超级电混，阿联酋80万+/欧洲近100万「最贵中国车」，60+国家/近800门店）；8月36,981辆（+109.8%）；千里科技3,443.88万收购智驾研发资产
  - entities/leapmotor.md - 上半年出口9.6万台（+372.6%）；意大利纯电市占率超25%；第二品牌2027 Q4定档（30万+）
  - entities/li-auto.md - i9实际售价36.98万（低于预期38.98-40.98万）；自研电池切换致宁德市值十天蒸发超7000亿
  - entities/xiaopeng.md - G9L 9/17-18上市23.18万起（纯电+超级增程）
  - entities/mercedes-benz.md - Momenta智驾扩至迈巴赫S级（首进百万级豪华燃油）；纯电CLA 24.9万起/866km；庄睦德9/29「高质量共创」
  - entities/bmw.md - iX3长轴26.99-33.99万一口价、CLTC最高919km（豪华首款破900km）、400kW快充10分钟427km
  - entities/stellantis.md - 神龙×Momenta全球战略（R7世界模型，Jeep/标致首搭）；博泰车联进Jeep全球供应；零跑意大利25%市占
  - entities/volvo.md - 史上最大产品计划：2030前13款新车/6款中国专供，放弃全面纯电化
  - entities/catl.md - 天行II商用车平台（重卡1000km/兆瓦快充25分钟80%/12年150万公里）；9月回购31.03亿；理想冲击市值蒸发7000亿
  - entities/changan.md - 8月集团14.09万（-22.6%）；糯玉米1.79万→31台（结构崩塌信号）
  - concepts/solid-state-battery.md - 丰田福冈良品率仅65%（vs液态95%）、成本2.3元/Wh「专利最多、产品最慢」
  - concepts/global-battery-competition.md - 出海专利警报：钠离子专利占全球75%但海外布局仅20%
  - concepts/new-forces-landscape-2026.md - 恒大汽车正式退出制造（洗牌信号增强）
  - auto-industry/suzuki-india-analysis.md - 补frontmatter；8月市占40.1%仍稳但2025财年年度首度跌破40%
- **导航更新**：index.md - Comparisons 5→6（+2026-09-china-sales-battle）；Total pages 273→274
- **索引完整性校验**：comm 输出为空（274页全部注册，缺失0）
- **核心洞察**：①结构换挡是9月主线——比亚迪增长引擎切海外（占比43%）、零跑超特斯拉中国、极氪9X立价80万+，自主攻防从国内卷到全球定价权；②外资反攻逻辑清晰——大众ID.AURA中方主导+奔驰中国智驾进迈巴赫+宝马iX3一口价919km，Stellantis三层中国供应链入局（零跑/Momenta/博泰）——「技术换市场」角色首次反转；③理想自研电池→宁德市值蒸发7000亿，「去宁化」从叙事变市值事件；④渗透率口径57.8% vs 8月65.8%差异大，需校准

## [2026-10-01] ingest | 每日Wiki整理（9个cron日报 + 盖世晚报）
- **新建**：
  - entities/gotion.md - 国轩高科：12.5亿美元入股大众PowerCo瓦伦西亚工厂49%（欧洲LFP中心）；PowerCo反入股国轩斯洛伐克/摩洛哥各49%；大众24%大股东背景——「绑定外资巨头换欧洲市场准入」路线
  - raw/articles/2026-10-01-daily-digest.md - 今日cron素材汇总（9月交付榜/南北丰田/L3试点牌/智驾域控TOP10/自研芯片出货/AI工程化）
- **更新（23页）**：
  - entities/toyota.md - 南北丰田合并落定（生产归广汽、销售50:25:25，成中国最大合资品牌）
  - entities/wenjie.md - 华为×赛力斯10/1再谈判（问界"专属专营"），模式博弈成鸿蒙智行最大内部变量
  - entities/leapmotor.md - 9月全球105,656台（+59%）；欧洲网点破1020家/36国；Q2首超斯巴鲁/三菱；D19/A05巴黎车展
  - entities/nio.md - 9月37,408台；第4,125座换电站+丝绸之路换电线贯通（西安—霍尔果斯）；与吉利换电联盟落地
  - entities/xiaopeng.md - 9月41,256台（Q3 118,390）；VLA 2.0新版（Master Agent）；X-Energy兆瓦闪充香港投运；图灵芯片20万片
  - entities/xiaomi-auto.md - 9月单月首破4万台，产能爬坡期结束
  - entities/huawei-auto.md - 鸿蒙智行9月37,490台累计破156万；ADS 4.1 P3评分4.46居首
  - entities/byd.md - 8月海豚销冠16,829+出口纪录14,947；兆瓦闪充2.0升10C；域控装机26%第一
  - entities/geely.md - Q2营收898亿（+14.1%）、净利51.2亿（+63%）、出海38%、单车收入12.6万
  - entities/bmw.md - 资本日：裁撤20%中国渠道+统一价；审查沈阳基地出口全球
  - entities/volvo.md - 7月ES90仅294辆、大中华区-27%；全球暂停白领招聘
  - entities/renault.md - Alpine A110纯电（800V/480Ps，2027对标718 EV）；印度9月20,180辆（-13.8%）
  - entities/shenxingzhe-8.md - 首发1000台售罄
  - entities/qingzhou.md - 单征程6M端到端NOA上理想L系，累计破100万台
  - concepts/l3-mandatory-standard.md - GB44721-2026发布确认（2027.7.1实施）；试点牌仅深蓝SL03/极狐阿尔法S
  - concepts/autonomous-driving-chips.md - 8月智驾域控装机TOP10占84%（比亚迪26%/德赛西威16.7%/华为10.5%）
  - concepts/auto-chip-self-develop.md - 自研芯片出货实证：小鹏图灵20万+大众定点、蔚来神玑55万、理想马赫超5万
  - concepts/eu-ev-market-2026.md - H1电+插混30.5%首超燃油；纯电份额25.7%；中国品牌纯电11.7%
  - concepts/ai-engineering-2026.md - 研发周期18-24月、云原生PLM+46.2%、盘古CV江汽99.99%、蔚来AI编程30%一次通过率
  - concepts/training-loop.md - 理想训练成本-75%、合成数据40%、极端场景+300%、难点错误率-47%
  - concepts/generative-engine-optimization.md - 88.6%消费者AI搜索购车决策、GEO"B2AI2C"范式
  - concepts/central-soe-restructuring-2026.md - 发改委9/26支持车企兼并重组（10→5淘汰赛政策背书）
  - comparisons/2026-09-china-sales-battle.md - 新势力9月交付榜（零跑105,656领跑/小鹏/小米破4万/鸿蒙智行/蔚来）
- **导航更新**：index.md - Entities/电池厂商1→2（+gotion）；Total pages 274→275（entities 102 / concepts 156 / comparisons 6 / auto-industry 10 / european-automakers 1）
- **索引完整性校验**：comm 输出为空（275页全部注册，缺失0）
- **核心洞察**：①南北丰田合并+发改委支持兼并重组，中日两侧产业集中度同步加速，「10→5淘汰赛」进入政策兑现期；②去英伟达化从口号变出货——图灵20万片+大众定点标志国产自研芯片首次进欧洲大厂供应链；③L3国标2027.7.1实施前，试点牌仅2款且不支持变道，法规保守度是量产最大约束；④零跑9月10.5万台领跑且欧洲网点破千，出海从"渠道铺设"进入"盈利验证"；⑤问界专属专营再谈判暴露鸿蒙智行多品牌利益分配的结构性矛盾
