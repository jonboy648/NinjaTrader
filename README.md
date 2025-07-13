# NinjaTrader Custom Trading Tools Repository

This repository contains a collection of custom indicators, trading strategies, and automated trading bots designed for the **NinjaTrader** trading platform.

## What is NinjaTrader?

NinjaTrader is a comprehensive trading platform used for trading futures, forex, stocks, and options. It provides advanced charting, market analysis, and automated trading capabilities.

## Repository Contents

### 🤖 Trading Strategies & Bots

- **SkyFire** (`SkyFire.cs` + `/SkyFire Bot/` folder) - An automated trading strategy with multiple versions including ATR-based stop loss and take profit functionality
- **GexBot** (`GexBot.cs`) - A trading bot with gamma exposure analysis capabilities
- **Killpips_Ninja** (`Killpips_Ninja.cs`) - A scalping strategy
- **DTCScalper** (`DTCScalper.cs`) - A day trading scalping indicator

### 📊 Custom Indicators

- **DeltaIntensity** (`DeltaIntensity.cs`) - Analyzes order flow and volume delta
- **FairValueGapICT** (`FairValueGapICT.cs`) - Inner Circle Trader fair value gap detection
- **FibonacciRetrace** (`FibonacciRetrace.cs`) - Automated Fibonacci retracement levels
- **LindaMACD** (`LindaMACD.cs`) - Custom MACD implementation
- **SqueezeMomentumIndicator** (`SqueezeMomentumIndicator.cs`) - Momentum and squeeze detection
- **Supertrend** (`Supertrend.cs`) - Trend following indicator
- **WaddahAttarExplosion** (`WaddahAttarExplosion.cs`) - Volatility and momentum indicator
- **TOWilliamsRenkoV12** (`TOWilliamsRenkoV12.cs`) - Renko chart based indicator
- **OptimusNinja** (`OptimusNinja.cs`) - Advanced trading indicator
- **Domdicator_Staging2** (`Domdicator_Staging2.cs`) - DOM (Depth of Market) analysis
- **ManciniNinja** (`ManciniNinja.cs`) - Custom trading indicator
- **PaperArms/Feet/Hands** (`Paper*.cs`) - Paper trading related indicators
- **ProfessorLines** (`ProfessorLines.cs`) - Support and resistance lines
- **Ricochet** (`Ricochet.cs`) - Price action indicator

### 🔊 Audio Alerts

- `Buy.wav` / `buy.wav` - Audio notification for buy signals
- `Sell.wav` / `sell.wav` - Audio notification for sell signals  
- `Imbalance.wav` / `imbalance.wav` - Audio notification for market imbalances

### ⚙️ Configuration Files

- `Default.xml` - Default NinjaTrader settings
- `NinjaTemplate.xml` - Custom template configuration
- `Lizards.xml` - Additional configuration file

### 📁 Additional Folders

- `/Campervanseth/` - Additional trading tools
- `/Optimus Indicator/` - Optimus indicator files
- `/SkyFire Bot/` - SkyFire strategy variations and documentation

## File Types

- **`.cs` files** - C# source code for indicators and strategies that can be compiled and used within NinjaTrader
- **`.xml` files** - Configuration and template files for NinjaTrader settings
- **`.wav` files** - Audio alert sounds for trade notifications
- **`.zip` files** - Packaged versions of strategies/indicators
- **`.txt` files** - Documentation and notes

## How to Use

1. **For Indicators**: Copy the `.cs` files to your NinjaTrader `Custom\Indicators` folder
2. **For Strategies**: Copy strategy `.cs` files to your NinjaTrader `Custom\Strategies` folder  
3. **For Audio**: Place `.wav` files in your NinjaTrader sounds folder
4. **Compile**: Use NinjaTrader's NinjaScript Editor to compile the code
5. **Apply**: Add the compiled indicators/strategies to your charts

## Important Notes

- These are custom-developed trading tools and should be used with caution
- Always test strategies on paper/simulation accounts before live trading
- Ensure you understand the logic and risk management of each tool before use
- Some tools may require specific NinjaTrader versions or additional dependencies

## Disclaimer

These trading tools are provided for educational and research purposes. Trading involves substantial risk and is not suitable for all investors. Past performance does not guarantee future results.