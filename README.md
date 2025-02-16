# Golang后端开发工程师 & Web3方向 60天强化复习计划

## 📌 每日安排（工作日3-4h/天，周末8-10h/天）
时间 | 内容 | 资源推荐 | 产出要求
--- | --- | --- | ---
08:00-09:30 | 算法攻坚（LeetCode+专项突破） | 《算法导论》+ LeetCode精选 | 每日2新题+旧题复盘（需Git提交记录）
19:30-21:30 | Golang核心机制深度解析 | 《Go语言高级编程》+ Go Blog | 手写GC触发机制流程图/Channel死锁案例集
周末上午 | Web3专题攻坚（智能合约+DeFi协议） | Solidity官方文档+《Mastering Ethereum》 | 实现ERC20代币合约+闪电贷模拟器
周末下午 | 系统设计实战（分布式系统+区块链架构） | 《Designing Data-Intensive Applications》 | 设计交易所撮合引擎架构图

## 📚 分模块攻略
### 算法模块（占比30%）
- **Week1-2**：基础数据结构强化
  - 重点攻克：链表双指针/二叉树遍历/堆栈应用
  - 必刷题单：LeetCode Hot 100前50题（侧重Golang实现）
- **Week3-4**：并发编程算法
  - 通道应用题：生产者消费者模式/工作池实现
  - 锁机制题：银行转账死锁问题/读写锁优化
- **Week5-6**：Web3特色算法
  - Merkle Tree实现/椭圆曲线加密基础
  - 交易排序算法/共识算法对比（PoW vs PoS）

### Golang核心（占比25%）
- **Week1**：运行时机制
  - GC三色标记法实现原理
  - Slice底层内存模型/Map扩容机制
- **Week2**：并发编程实战
  - Channel高级模式（fan-in/fan-out）
  - sync.Pool应用场景/race condition检测
- **Week3**：框架深度
  - Gin中间件开发（JWT鉴权实现）
  - net/http源码解析（Handler注册机制）

### 中间件专题（占比20%）
- **Week4**：Redis深度
  - 分布式锁Redlock实现
  - 缓存穿透/雪崩解决方案
- **Week5**：PostgreSQL优化
  - 索引失效场景分析
  - MVCC机制与事务隔离级别
- **Week6**：Kafka实战
  - 消息可靠性保证方案
  - Consumer Group重平衡策略

### Web3专项（占比15%）
- **Week7**：以太坊生态
  - EVM执行原理分析
  - 智能合约安全漏洞（重入攻击/溢出）
- **Week8**：Solana特色
  - Sealevel并行执行原理
  - POH（Proof of History）机制解析

## 🔍 模拟实战
- **每周三/五晚**：Pair Programming（使用CoderPad）
- **每周六下午**：全链路压力面试（含白板设计）
- **次日上午**：STAR法则复盘（重点改进技术表达）

## ⚠️ 注意事项
1. **算法错题本**：按题型分类（标注时间/空间复杂度优化路径）
2. **技术亮点库**：
   - 准备3个高并发场景解决方案（含压测数据）
   - 开发1个Web3相关开源工具（如链上数据分析器）
3. **项目升级方案**：
   - 在现有项目添加：分布式追踪（OpenTelemetry）
   - 实现：基于零知识证明的身份验证模块
4. **简历Checklist**：
   - 量化成果（如：QPS从2000提升至15000）
   - 突出Web3双栈能力（传统后端+区块链开发）

## 📈 里程碑规划
| 阶段 | 时间 | 验收标准 |
|---|---|---|
| 筑基期 | Week1-2 | 算法周赛稳定AC 3题+Go runtime思维导图 |
| 强化期 | Week3-4 | 实现分布式限流中间件+Redis集群方案设计 |
| 突破期 | Week5-6 | 完成DeFi借贷合约开发+通过CKA认证考试 |
| 冲刺期 | Week7-8 | 开源项目Star破百+模拟面试通过率90% |

## 🔗 推荐资源包
1. 算法：《剑指Offer专项突破版》+ LeetCode企业题库
2. Golang：《Go语言原本》+ Dave Cheney博客
3. Web3：Chainlink官方课程 + Solana开发者文档
4. 系统设计：《Grokking Modern System Design》+ 阿里云架构白皮书

请按日更新GitHub仓库记录进度（建议包含：code snippets/design docs/interview notes）```
