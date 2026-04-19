# alpha-td-countdown

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nikolas-joyce/alpha-td-countdown/blob/main/notebooks/alpha_td_countdown.ipynb)

> TD Sequential Countdown (13-bar) alpha signal — backtest + parameter sweep

> After a 9-bar setup completes, the 13-bar countdown tracks qualifying closes (each close <= low two bars prior for bears; close >= high two bars prior for bulls). Full completion signals deep exhaustion — lower frequency than TD Setup, higher conviction.

## Notebook structure
| Section | Description |
|---------|-------------|
| 0 | Install & imports |
| 1 | Config & data |
| 2 | Helper functions |
| 3 | TD Sequential engine |
| 4 | V2 signal generation — conventional & contrarian polarity |
| 5 | Returns & performance |
| 6 | Per-ticker breakdown |
| 7 | Parameter sensitivity (countdown count 9–13) |
| 8 | Representative equity curves |
| 9 | Export signals for td-swarm |

**Run all cells top-to-bottom in a fresh Colab runtime.**

