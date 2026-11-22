## Hi, I'm Ed

**C++ / Python developer with a PhD in vehicle routing, moving into quantitative finance.**

I spent ten years working out where vans should go. These days I'm more interested in where prices go, with a healthy respect for how much harder that is.

### Things I've built

Mostly at a UK utility infrastructure company, 2015 to 2026:

- **An engineer scheduling optimiser.** I designed and built it solo in C++ using Guided Variable Neighbourhood Search, with time windows and skills constraints for engineers across the UK. It cut driving time by up to 30%, roughly **£2M a year**. It ran behind a REST service, with a web UI for tuning the heuristics and inspecting schedules.
- **A UK road-network distance matrix** (C++, Boost). I built a directed graph from OpenStreetMap and snapped postcodes to it with a kd-tree. One-to-many Dijkstra then produced a 9-million-entry travel-time matrix in 30 minutes. Routes between near-identical postcodes are fuzzy-matched from a PostgreSQL cache, so the cache never grew to billions of rows.
- **A utility network design portal** for gas, electricity and district heating. You draw a network on the map, press *Design*, and graph algorithms size every pipe, cable and asset from source to demand, flagging loops and invalid connections on the way. Built on OpenLayers, MapServer, PostgreSQL and PostGIS. I was team lead, then tech lead, in the GIS team.
- **On-device machine learning.** I trained a TensorFlow model to spot gas-meter fitting defects in site photos, then converted it to TensorFlow Lite so it runs offline on engineers' tablets.

### Quant projects

I got into trading at university and have blown up a few small accounts since. That's why my projects spend a lot of time on not fooling yourself.

- **[AIR](https://github.com/eddykent/AIR)** is my FX research framework: indicators vectorized across 28 pairs at once, chart pattern finders, filters, bid/ask backtesting and a strategy finder. It's retired now, with nine tour notebooks, including one showing why the strategy finder's best results are mostly luck.
- **[Backtest Kit Lite](https://github.com/eddykent/backtest-kit-lite)** is a small, tested, vectorized backtesting engine for stocks.

### Toolbox

**C++** (STL, Boost, CMake) · **Python** (numpy, pandas, scipy, TensorFlow) · **SQL** (PostgreSQL / PostGIS, SQL Server) · **Optimisation** (metaheuristics, MILP with CPLEX and GLPK) · **Also** C#, JavaScript, Linux, git, LaTeX

### Education

- **PhD, Computer Science (Operational Research)**, University of Nottingham, 2016. Thesis on vehicle routing with synchronisation constraints in forestry operations, solved with heuristics benchmarked against MILP lower bounds.
- **BSc Mathematics and Computer Science (Joint Hons)**, University of Nottingham, 2011.
- Paper: *Vehicle Routing in a Forestry Commissioning Operation Using Ant Colony Optimisation*, Theory and Practice of Natural Computing, Granada, 2014.

### What I'm looking for

A quant developer role, building research tools, backtesters and the data plumbing behind them, in a team that enjoys arguing about whether an edge is real. Remote or hybrid; a couple of days a week in London works well. Based near Bristol, UK.

### Off the clock

Guitar (classic rock to metal), cooking (my dad is a regular and only slightly biased critic), astronomy (and far too many Brian Cox documentaries), and Renegade X, a community-run game I'd love to help develop one day.

---

[LinkedIn](https://www.linkedin.com/in/edward-kent-737b574a/) is the best way to reach me.
