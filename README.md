# GoshenBot
LiquiditySweep.mq5, complete with:  Sweep Low detection and 3-bar confirmation  Volume spike filter  Risk-based position sizing  Dynamic TP (1.5× risk) and SL at the sweep low  Time &amp; cooldown filters  Max position stacking  Partial close and breakeven trailing stop  Robust logging for each stage.

RSI divergence filter: detecting hidden bullish divergence over a customizable lookback

Dynamic risk-scaling: ATR-driven risk between MinRiskPercent and MaxRiskPercent

Input parameters for all new features (RSI lookback, ATR period, min/max risk)

Robust CheckRSIDivergence function implementing hidden divergence

Cleaned up trade management with partial closes and breakeven trailing-stop

Adaptive Reward Ratios (BaseRewardRatio, MinRewardRatio, MaxRewardRatio) scaled by ATR

Multi-timeframe Trend Filter using a H4 50-period SMA

Advanced Money Management: optional Kelly sizing with UseKellyMM and KellyFraction

Refactored parameter names and normalized lots
