# AI产业链周报：2026-06-29 至 2026-07-05

## 1. 本周总判断
过去7天，全球AI产业的边际增量主要来自“Agent进入生产环境”和“推理基础设施金融化/工业化”两条线，而不是六大云厂商正式上修CapEx。NVIDIA连续发布关于GB300在Azure落地、推理成本优化、AI工厂融资模式和美国本土制造链扩张的官方信息，说明需求叙事正从训练集群继续外溢到高利用率推理、主权AI与多租户AI工厂。Google与Microsoft则分别强化了Agent API、托管Agent、企业安全治理，进一步证明大模型平台正从模型能力竞争走向平台能力、工具链和安全能力竞争。对A股映射而言，AI服务器、光模块、PCB、液冷、电力与数据中心仍然是更容易承接海外增量的方向，但本周需要警惕的风险是：正式CapEx口径并未同步上修，电力/监管约束在AI数据中心建设中的重要性继续抬升。

- 全球AI CapEx：持平
- NVIDIA需求信号：增强
- A股AI基础设施映射：偏利好
- 本周风险等级：中

## 2. 全球AI CapEx跟踪

### Microsoft
- 本周是否有新信息：有，但主要是Agent安全与Azure上GB300落地，不是正式CapEx修订。
- CapEx是否上修 / 维持 / 下修：维持。
- 数据中心或AI基础设施建设是否加速：边际上继续推进，但本周未见Microsoft官方新增CapEx数字。
- 关键数据或原文要点：Microsoft Security 2026-06-30指出企业AI Agent正在从“读内容”转向“执行动作”，Azure AI Foundry与Copilot Studio正连接企业系统；NVIDIA 2026-06-29披露Anthropic Claude在Microsoft Foundry中已基于Azure上的NVIDIA GB300 Blackwell Ultra实现GA，说明Azure侧已在承接更先进GPU的生产级Agent工作负载。
- 来源链接：[Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/2026/06/30/securing-ai-agents-ai-tools-move-from-reading-acting/)；[NVIDIA: Claude Meets Blackwell Ultra](https://blogs.nvidia.com/blog/anthropic-nvidia-gb300-blackwell-ultra-microsoft-azure/)
- 对AI产业链的含义：正式CapEx未上修，但Azure继续承接更高阶GPU和Agent负载，利好AI服务器、交换/互连、液冷与企业Agent生态。

### Amazon / AWS
- 本周是否有新信息：本周未发现明确新增信息。
- CapEx是否上修 / 维持 / 下修：不足以判断边际变化，暂按维持看待。
- 数据中心或AI基础设施建设是否加速：本周未见AWS官方新增正式表述。
- 关键数据或原文要点：本周未发现AWS官方新增CapEx、数据中心建设或AI基础设施重大口径更新。
- 来源链接：[Amazon IR quarterly results](https://ir.aboutamazon.com/quarterly-results/default.aspx)
- 对AI产业链的含义：AWS仍是核心需求方，但本周缺乏新增正式信号，不宜据此推导CapEx再加速。

### Alphabet / Google
- 本周是否有新信息：有，主要在Agent API、全栈AI平台和端侧/本地模型方向。
- CapEx是否上修 / 维持 / 下修：维持。
- 数据中心或AI基础设施建设是否加速：本周未见官方新增CapEx数字，但Google继续强调从TPU到平台到终端的全栈布局。
- 关键数据或原文要点：Google 2026-07-01发布6月AI回顾，提到Gemma 4 12B可在16GB内存的笔记本本地运行，Google Home Speaker built for Gemini上线；Google 2026-06-29解释其“full-stack AI”逻辑，明确覆盖TPU、Gemini模型、Gemini Enterprise Agent Platform和终端接口；Google 还宣布Interations API达到GA，支持Managed Agents、后台执行、工具组合和多模态生成。
- 来源链接：[Google June AI roundup](https://blog.google/innovation-and-ai/technology/ai/google-ai-updates-june-2026/)；[Google full-stack AI explainer](https://blog.google/innovation-and-ai/technology/ai/full-stack-ai-explainer/)；[Google Interactions API GA](https://blog.google/innovation-and-ai/technology/developers-tools/interactions-api-general-availability/)
- 对AI产业链的含义：Google本周的重点不是追加资本开支，而是把“模型-平台-Agent-终端”打通，说明推理与端侧AI仍是中长期投入重点。

### Meta
- 本周是否有新信息：本周未发现明确新增信息。
- CapEx是否上修 / 维持 / 下修：维持。
- 数据中心或AI基础设施建设是否加速：本周未见新的正式CapEx或数据中心建设口径更新。
- 关键数据或原文要点：监控窗口内未见Meta官方新增AI CapEx或数据中心重要披露。
- 来源链接：[Meta financials](https://investor.fb.com/financials/)；[Meta Newsroom](https://about.fb.com/news/)
- 对AI产业链的含义：Meta仍是全球AI基础设施核心买方之一，但本周信息不足以判断边际变化。

### Oracle
- 本周是否有新信息：本周未发现明确新增信息。
- CapEx是否上修 / 维持 / 下修：维持。
- 数据中心或AI基础设施建设是否加速：本周未见新增正式口径。
- 关键数据或原文要点：上周Oracle仍是全球AI CapEx最强边际增量之一，但本监控窗口内未见新的官方追加披露。
- 来源链接：[Oracle quarterly results](https://investor.oracle.com/financials/quarterly-results/default.aspx)
- 对AI产业链的含义：Oracle仍是观察AI云产能和订单兑现的重要样本，但本周没有新的正式增量。

### Tesla
- 本周是否有新信息：本周未发现明确新增信息。
- CapEx是否上修 / 维持 / 下修：维持。
- 数据中心或AI基础设施建设是否加速：不足以判断。
- 关键数据或原文要点：本周未见Tesla官方新增关于Dojo、训练算力、Robotaxi扩张或Optimus量产的正式重大披露。
- 来源链接：[Tesla IR](https://ir.tesla.com/)；[Tesla AI](https://www.tesla.com/AI)
- 对AI产业链的含义：机器人与自动驾驶仍是长期方向，但本周没有新增正式信号支持边际上修判断。

## 3. NVIDIA核心跟踪

### 3.1 数据中心业务
- 本周重要信息：NVIDIA 2026-07-01提出新的AI工厂合作模式，面向AI云提供收入分成和信用支持，帮助多租户AI工厂更快上线。
- 关键数据：Sharon AI计划部署最多40,000颗NVIDIA Grace Blackwell GB300 GPU；Firmus在印尼巴淡岛建设的DSX AI factory campus预计可扩展至360MW、最多170,000颗NVIDIA GPU。
- 来源链接：[NVIDIA Unlocks AI Compute at Scale](https://blogs.nvidia.com/blog/nvidia-unlocks-ai-compute-at-scale-capital-partners-to-power-ai-infrastructure-buildout/)
- 对AI产业链的含义：这说明NVIDIA不只卖卡，也在推动算力资产证券化/金融化，数据中心需求正在从超大云厂商扩展到AI云和区域算力运营商。

### 3.2 GPU需求
- 本周重要信息：NVIDIA反复把需求表述从训练扩展到“持续运行的AI factories”和高并发agentic inference，说明GPU需求结构继续向推理扩张。
- 关键数据：NVIDIA 2026-06-30称其Blackwell平台在一个月内已把DeepSeek V4模型的token成本最多降低5倍；多项系统级优化合并后可带来最高20倍吞吐增益。
- 来源链接：[How NVIDIA’s Inference Software Stack Powers the Lowest Token Cost](https://blogs.nvidia.com/blog/inference-software-lowest-token-cost/)
- 对AI产业链的含义：市场需求逻辑已从“抢训练卡”延伸到“用更低token成本跑生产推理”，这对高带宽互连、服务器整机、液冷和供电的持续需求更有利。

### 3.3 Blackwell出货
- 本周重要信息：Anthropic Claude在Microsoft Foundry中基于Azure上的NVIDIA GB300 Blackwell Ultra实现GA，是本周最清晰的Blackwell生产级落地信号之一。
- 关键数据：Claude运行于NVIDIA GB300 NVL72系统，并配套Quantum-X800 InfiniBand网络。
- 来源链接：[Claude Meets Blackwell Ultra](https://blogs.nvidia.com/blog/anthropic-nvidia-gb300-blackwell-ultra-microsoft-azure/)
- 对AI产业链的含义：Blackwell不再只是样机或预热，而是继续向Azure企业客户交付，利好AI服务器、光互连、交换和机柜级散热链条。

### 3.4 HBM供应
- 本周重要信息：本周未见NVIDIA或主要HBM供应商披露新的正式供需拐点。
- 关键数据：不足以判断。
- 来源链接：[NVIDIA Newsroom archive](https://nvidianews.nvidia.com/news)；[NVIDIA investor relations](https://investor.nvidia.com/)
- 对AI产业链的含义：虽然没有新的HBM官方口径，但Blackwell和GB300持续落地本身说明高带宽内存仍是关键配套环节；本周不足以判断瓶颈是否实质缓解。

### 3.5 财报 / 指引 / 订单
- 本周重要信息：本周没有新的NVIDIA财报或正式季度指引更新，但订单/建设侧出现更强的“持续扩张”信号。
- 关键数据：NVIDIA 2026-07-01披露计划与合作伙伴在美国生产最高5000亿美元AI基础设施；涉及TSMC Phoenix、Foxconn Houston、Wistron Fort Worth，以及Corning、Lumentum、Coherent、Amkor等供应链伙伴。
- 来源链接：[NVIDIA and Partners Build in America, for America](https://blogs.nvidia.com/blog/nvidia-and-partners-build-in-america-for-america/)
- 对AI产业链的含义：没有新的季度指引，但供应链组织方式更像在为更长周期需求做产能与本土制造准备。

### 3.6 市场对AI需求的判断
- 本周重要信息：NVIDIA、Google、Microsoft的官方口径都在强化“Agent进入生产环境”的判断；Google把Gemini/TPU/Agent平台/终端打包成全栈，Microsoft则把企业Agent安全单独拉出来，说明企业部署进入更深水区。
- 关键数据：Google Interactions API已GA，支持Managed Agents、后台执行和工具混用；Microsoft援引IDC预计企业活跃AI Agent数量将从2025年的2860万增长到2030年的22亿以上。
- 来源链接：[Google Interactions API GA](https://blog.google/innovation-and-ai/technology/developers-tools/interactions-api-general-availability/)；[Microsoft Security Blog](https://www.microsoft.com/en-us/security/blog/2026/06/30/securing-ai-agents-ai-tools-move-from-reading-acting/)
- 对AI产业链的含义：需求判断继续偏正面，但竞争焦点正从“谁有模型”转向“谁有平台、工具、安全、推理效率和交付能力”。

## 4. A股AI产业链映射

### 光模块
- 全球驱动因素：NVIDIA 2026-07-01明确把Coherent、Corning、Lumentum列为AI基础设施扩张的重要网络/光连接伙伴；GB300在Azure落地也继续强化高带宽互连需求。
- 本周重要信息：美国本土AI基础设施扩张强调先进光连接、激光器、InP产线和研发协同。
- A股映射逻辑：海外AI工厂扩产仍利好800G/1.6T、硅光、CPO和高速光模块链条，A股光模块方向的核心仍是订单持续性、ASP和客户集中度。
- 风险：本周正式CapEx未普遍上修；如果AI工厂建设受制于电力或审批，光模块交付节奏也可能后移。
- 来源链接：[NVIDIA and Partners Build in America, for America](https://blogs.nvidia.com/blog/nvidia-and-partners-build-in-america-for-america/)

### PCB
- 全球驱动因素：GB300 NVL72、AI服务器和机柜级系统对高速PCB、背板、连接器的需求继续增强。
- 本周重要信息：Foxconn将生产GB300 tray modules，Wistron将组装和测试NVIDIA AI systems，说明板级/系统级配套仍在扩张。
- A股映射逻辑：高多层、高速、高散热要求的PCB方向仍受益于AI服务器升级。
- 风险：若订单更多集中在北美本土化制造，A股公司仍要看是否真正进入海外客户BOM与认证体系。
- 来源链接：[NVIDIA and Partners Build in America, for America](https://blogs.nvidia.com/blog/nvidia-and-partners-build-in-america-for-america/)

### AI服务器
- 全球驱动因素：Azure上GB300 GA、Sharon AI 40,000颗GB300部署计划、Firmus 170,000 GPU园区规划，都指向整机和机柜需求延续。
- 本周重要信息：NVIDIA把AI cloud、多租户AI factory和融资模式绑定，说明服务器需求不再局限于传统超大云。
- A股映射逻辑：服务器整机、电源、机柜、ODM配套和测试验证方向继续受益。
- 风险：若融资驱动的AI云需求低于预期，订单兑现可能波动；本周仍缺少更多云厂商正式CapEx同步验证。
- 来源链接：[NVIDIA Unlocks AI Compute at Scale](https://blogs.nvidia.com/blog/nvidia-unlocks-ai-compute-at-scale-capital-partners-to-power-ai-infrastructure-buildout/)；[Claude Meets Blackwell Ultra](https://blogs.nvidia.com/blog/anthropic-nvidia-gb300-blackwell-ultra-microsoft-azure/)

### 液冷与电力
- 全球驱动因素：NVIDIA本周再次把power systems、cooling、energy grids列为AI基础设施核心组成部分，说明功率密度约束继续上升。
- 本周重要信息：AI工厂建设叙事正在从“买GPU”转向“电力、冷却、建设、融资一起解决”。
- A股映射逻辑：液冷、UPS、储能、变压器、电网设备和温控仍是较强映射方向。
- 风险：美国对数据中心电价和审批的争议继续升温，若监管趋严，可能拖慢项目落地节奏。
- 来源链接：[NVIDIA and Partners Build in America, for America](https://blogs.nvidia.com/blog/nvidia-and-partners-build-in-america-for-america/)；[The Guardian: Ratepayer Protection Act and datacenters](https://www.theguardian.com/us-news/2026/jul/05/ratepayer-protection-act-datacenters)

### 数据中心与算力租赁
- 全球驱动因素：NVIDIA推出收入分成和信用支持模式，显著利好AI cloud、区域算力运营商和租赁型算力平台。
- 本周重要信息：Firmus AI cloud园区预计扩展至360MW、最多170,000 GPU；Sharon AI最多部署40,000颗GB300。
- A股映射逻辑：若海外算力租赁模式成立，国内IDC、算力调度、租赁平台和园区基础设施会反复被市场映射。
- 风险：该模式仍处早期，融资成本、上座率、客户付费能力和电力可得性都需要持续验证。
- 来源链接：[NVIDIA Unlocks AI Compute at Scale](https://blogs.nvidia.com/blog/nvidia-unlocks-ai-compute-at-scale-capital-partners-to-power-ai-infrastructure-buildout/)

### 国产AI芯片与半导体
- 全球驱动因素：Google 2026-06-29继续强调TPU+模型+平台+终端的一体化全栈路线；NVIDIA则继续强化本土制造、先进封装、系统集成与完整供应链。
- 本周重要信息：Google明确提到自研TPU和十年以上的基础设施投资逻辑；NVIDIA强调从晶圆、封装到系统与AI工厂的全链条组织能力。
- A股映射逻辑：国产AI芯片、先进封装、材料设备方向的中长期逻辑仍在于“全栈可控”和关键环节替代，而非短期情绪。
- 风险：本周暂无明确新增国产替代催化，继续观察真实订单、良率、生态兼容和软件栈成熟度。
- 来源链接：[Google full-stack AI explainer](https://blog.google/innovation-and-ai/technology/ai/full-stack-ai-explainer/)；[NVIDIA and Partners Build in America, for America](https://blogs.nvidia.com/blog/nvidia-and-partners-build-in-america-for-america/)

### 机器人与自动驾驶
- 全球驱动因素：NVIDIA 2026-06-30继续强调物理AI时代需要从仿真、训练、加速计算、AI模型、中间件到边缘部署的完整栈。
- 本周重要信息：Isaac ROS继续面向移动机器人、操作机器人和人形机器人，支持工作站、DGX Spark与Jetson边缘系统。
- A股映射逻辑：机器人链条更受益于“软件栈+边缘算力+传感器+执行器”整体成熟，而不只是单点硬件主题。
- 风险：本周没有特斯拉/主要整车厂新的正式量产与订单披露，自动驾驶和人形机器人仍需警惕估值跑得快于兑现。
- 来源链接：[How Jaiveer Singh Is Helping Robots — and Developers — Move Faster](https://blogs.nvidia.com/blog/nvidia-life-jaiveer-singh/)

## 5. ETF观察方向
- 人工智能ETF：适合观察逻辑是Agent平台、AI应用和基础设施的景气共振；当前主要风险是主题过热但业绩兑现分化；更适合右侧确认。
- 算力ETF：适合观察逻辑是NVIDIA需求增强、AI服务器与数据中心配套持续扩张；当前主要风险是正式CapEx未同步全面上修；更适合左侧观察后等待右侧确认。
- 半导体ETF：适合观察逻辑是国产替代、先进封装、材料设备和AI芯片全栈能力；当前主要风险是行业景气与估值错配；更适合左侧观察。
- 通信ETF：适合观察逻辑是光模块、高速互连、CPO和算力网络建设；当前主要风险是客户集中和建设节奏波动；更适合右侧确认。
- 机器人ETF：适合观察逻辑是物理AI、边缘算力、执行器和工业场景落地；当前主要风险是量产兑现慢；更适合左侧观察。
- 科创50ETF：适合观察逻辑是硬科技平台化收益，覆盖半导体和高端制造；当前主要风险是风格切换；更适合左侧观察。
- 红利ETF：适合观察逻辑是对冲AI成长波动与电力/政策不确定性；当前主要风险是若成长再加速则相对弹性不足；更适合作为防守型右侧平衡观察。

## 6. 本周风险清单
- 产业风险：六大CapEx公司本周大多没有新的正式上修口径。影响方向：压制“全面再加速”预期。后续观察：下一轮财报与正式电话会。
- 估值风险：Agent、算力、机器人叙事容易前置交易。影响方向：主题波动放大。后续观察：订单、收入、毛利率兑现。
- 政策风险：数据中心电价、审批、环保和社区阻力上升。影响方向：拖慢园区建设和上架节奏。后续观察：美国联邦/州级数据中心监管与公用事业政策。
- 技术路线风险：训练红利向推理和Agent迁移后，胜负手转向软件栈、token成本和平台能力。影响方向：单纯堆硬件公司的溢价可能收敛。后续观察：推理效率、开发者生态和Agent平台渗透。
- 供应链风险：HBM、本土制造、先进封装和电力配套仍可能成为瓶颈。影响方向：限制Blackwell与AI服务器放量。后续观察：HBM厂商、封装厂、光模块和电力设备新增口径。
- 业绩兑现风险：若AI云和区域算力运营商的高利用率未兑现，融资驱动的AI工厂模型可能承压。影响方向：对IDC、算力租赁和服务器链条形成波动。后续观察：上座率、客户结构、持续付费能力。

## 7. 下周跟踪重点
1. Microsoft、Amazon、Google、Meta、Oracle、Tesla是否出现新的正式CapEx或数据中心建设口径？
2. NVIDIA是否继续披露GB300/Blackwell在更多云厂商或企业客户中的GA与量产信息？
3. HBM三大厂是否出现新的供需、价格或交付节奏官方表述？
4. AI工厂融资模式能否扩展到更多AI cloud/主权AI项目？
5. Google Interactions API GA后，是否会带来更多Agent平台商业化案例？
6. Microsoft是否继续给出Azure AI Foundry、Copilot Studio或企业Agent的新增客户/安全治理信号？
7. 美国数据中心电力、审批、监管阻力是否继续上升？
8. 光模块、液冷、电力设备相关海外供应商是否出现新增扩产或订单披露？
9. 机器人与自动驾驶是否出现来自Tesla或NVIDIA生态的新量产/部署证据？
10. A股半年报预告中，哪些公司能把海外AI基础设施景气转化为订单、收入和利润？
