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
