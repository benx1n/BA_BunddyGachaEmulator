# BA_BuddyGachaEmulator

## 简介
随便写的抽卡模拟，图一乐
## 使用
Deck1和Deck2分别为两种发牌模型
TOTAL_TOKENS每次抽取的代币
NUM_SIMULATIONS模拟次数

    TOTAL_TOKENS = 120000
    NUM_SIMULATIONS = 100
    # 创建模拟抽卡类
    simulation = Simulation(TOTAL_TOKENS, NUM_SIMULATIONS, Deck1)
    # 调用simulate_strategies()获取抽牌数和奖励统计
    average_results, average_rewards = simulation.simulate_strategies()
    # 分析
    print_strategy_differences(average_results, average_rewards)
