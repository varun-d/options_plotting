# Learning Options

A quick Jupyter notebook exploring options

## Usage

Create your option set with current stock spot price
``` my_options = OptionPosition(100) # Add current spot price ```

Add a single long call (multiples coming soon)
Params are strike price, premium and "long" or "short" position
``` rkt_vertical_debit.add_call(95, 7.5, "long") ```

Add a single short call (multi coming soon)
Params are strike price, premium and "long" or "short" position
``` rkt_vertical_debit.add_call(110, 2.5, "short") ```

Plot all payoffs, not including totals
```rkt_vertical_debit.plot_all_payoffs()```

Plot totals (works only for calls for now?)
```rkt_vertical_debit.plot_tot_payoff()```

## ToDo

1. Fix puts totals? Yes, tested and working now.
2. Add ability to add multiple units of contracts to see change in graph
3. Awesome feature: Add normal distribution of underlying asset as overlay to see prob of profit and price movement. With IV and time?

