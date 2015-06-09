This is the accompany source codes for my book 'Mastering Python for Finance'.


(ISBN-10: 1784394513, ISBN-13: 978-1784394516)

Available on major sales channels including Amazon,
Safari Online and Barnes & Noble, in paperback, Kindle and ebook.

Get it from:
- http://www.amazon.com/Mastering-Python-Finance-James-Weiming/dp/1784394513
- https://www.packtpub.com/big-data-and-business-intelligence/mastering-python-finance

![alt text](https://d255esdrn735hr.cloudfront.net/sites/default/files/imagecache/ppv4_main_book_cover/4516OS_Mastering%20Python%20for%20Finance.jpg "Mastering Python for Finance")

Table of Contents
===
1. Python for Financial Applications
    - Is Python for me?
        - Free and open source
        - High-level, powerful, and flexible
        - A wealth of standard libraries
    - Objected-oriented versus functional programming
        - The object-oriented approach
        - The functional approach
        - Which approach should I use?
    - Which Python version should I use?
    - Introducing IPython
        - Getting IPython
        - Using pip
        - The IPython Notebook
            - Notebook documents
            - Running the IPython Notebook
            - Creating a new notebook
        - Notebook cells
            - Code cell
            - Markdown cell
            - Raw NBConvert cell
            - Heading cells
        - Simple exercises with IPython Notebook
            - Creating a notebook with heading and Markdown cells
            - Saving notebooks
            - Mathematical operations in cells
            - Displaying graphs
            - Inserting equations
            - Displaying images
            - Inserting YouTube videos
            - Working with HTML
            - The pandas DataFrame object as an HTML table
        - Notebook for finance
    - Summary
2. The Importance of Linearity in Finance
    - The capital asset pricing model and the security market line
    - The Arbitrage Pricing Theory model
    - Multivariate linear regression of factor models
    - Linear optimization
        - Getting PuLP
        - A simple linear optimization problem
        - Outcomes of linear programs
        - Integer programming
            - An example of an integer programming model with binary conditions
            - A different approach with binary conditions
    - Solving linear equations using matrices
    - The LU decomposition
    - The Cholesky decomposition
    - The QR decomposition
        - Solving with other matrix algebra methods
            - The Jacobi method
            - The Gauss-Seidel method
    - Summary
3. Nonlinearity in Finance
    - Nonlinearity modeling
    - Examples of nonlinear models
        - The implied volatility model
        - The Markov regime-switching model
        - The threshold autoregressive model
        - Smooth transition models
    - An introduction to root-finding
    - Incremental search
    - The bisection method
    - Newton's method
    - The secant method
    - Combining root-finding methods
    - SciPy implementations
        - Root-finding scalar functions
        - General nonlinear solvers
    - Summary
4. Numerical Procedures
    - Introduction to options
    - Binomial trees in options pricing
        - Pricing European options
            - Are these formulas relevant to stocks? What about futures?
        - Writing the StockOption class
        - Writing the BinomialEuropeanOption class
        - Pricing American options with the BinomialTreeOption class
        - The Cox-Ross-Rubinstein model
            - Writing the BinomialCRROption class
        - Using a Leisen-Reimer tree
            - Writing the BinomialLROption class
    - The Greeks for free
        - Writing the BinomialLRWithGreeks class
    - Trinomial trees in options pricing
        - Writing the TrinomialTreeOption class
    - Lattices in options pricing
        - Using a binomial lattice
        - Writing the BinomialCRROption class
        - Using the trinomial lattice
            - Writing the TrinomialLattice class
    - Finite differences in options pricing
        - The explicit method
            - Writing the FiniteDifferences class
            - Writing the FDExplicitEu class
        - The implicit method
            - Writing the FDImplicitEu class
        - The Crank-Nicolson method
            - Writing the FDCnEu class
        - Pricing exotic barrier options
            - A down-and-out option
            - Writing the FDCnDo class
        - American options pricing with finite differences
            - Writing the FDCnAm class
    - Putting it all together – implied volatility modeling
        - Implied volatilities of AAPL American put option
    - Summary
5. Interest Rates and Derivatives
    - Fixed-income securities
    - Yield curves
    - Valuing a zero-coupon bond
        - Spot and zero rates
    - Bootstrapping a yield curve
    - Forward rates
    - Calculating the yield to maturity
    - Calculating the price of a bond
    - Bond duration
    - Bond convexity
    - Short-rate modeling
        - The Vasicek model
        - The Cox-Ingersoll-Ross model
        - The Rendleman and Bartter model
        - The Brennan and Schwartz model
    - Bond options
        - Callable bonds
        - Puttable bonds
        - Convertible bonds
        - Preferred stocks
    - Pricing a callable bond option
        - Pricing a zero-coupon bond by the Vasicek model
        - Value of early-exercise
        - Policy iteration by finite differences
        - Other considerations in callable bond pricing
    - Summary
6. Interactive Financial Analytics with Python and VSTOXX
    - Volatility derivatives
        - STOXX and the Eurex
        - The EURO STOXX 50 Index
        - The VSTOXX
        - The VIX
    - Gathering the EUROX STOXX 50 Index and VSTOXX data
    - Merging the data
    - Financial analytics of SX5E and V2TX
    - Correlation between SX5E and V2TX
    - Calculating the VSTOXX sub-indices
        - Getting the OESX data
        - Formulas to calculate the VSTOXX sub-index
        - Implementation of the VSTOXX sub-index value
        - Analyzing the results
    - Calculating the VSTOXX main index
    - Summary
7. Big Data with Python
    - Introducing big data
    - Hadoop for big data
        - HDFS
        - YARN
        - MapReduce
    - Is big data for me?
    - Getting Apache Hadoop
        - Getting a QuickStart VM from Cloudera
        - Getting VirtualBox
        - Running Cloudera VM on VirtualBox
    - A word count program in Hadoop
        - Downloading sample data
        - The map program
        - The reduce program
        - Testing our scripts
        - Running MapReduce on Hadoop
        - Hue for browsing HDFS
    - Going deeper – Hadoop for finance
        - Obtaining IBM stock prices from Yahoo! Finance
        - Modifying the map program
        - Testing our map program with IBM stock prices
        - Running MapReduce to count intraday price changes
        - Performing analysis on our MapReduce results
    - Introducing NoSQL
        - Getting MongoDB
        - Creating the data directory and running MongoDB
            - Running MongoDB from Windows
            - Running MongoDB from Mac OS X
        - Getting PyMongo
        - Running a test connection
        - Getting a database
        - Getting a collection
        - Inserting a document
        - Fetching a single document
        - Deleting documents
        - Batch-inserting documents
        - Counting documents in the collection
        - Finding documents
        - Sorting documents
        - Conclusion
    - Summary
8. Algorithmic Trading
    - Introduction to algorithmic trading
    - List of trading platforms with public API
    - Which is the best programming language to use?
    - System functionalities
    - Algorithmic trading with Interactive Brokers and IbPy
        - Getting Interactive Brokers' Trader WorkStation
        - Getting IbPy – the IB API wrapper
        - A simple order routing mechanism
    - Building a mean-reverting algorithmic trading system
        - Setting up the main program
        - Handling events
        - Implementing the mean-reverting algorithm
        - Tracking our positions
    - Forex trading with OANDA API
        - What is REST?
        - Setting up an OANDA account
        - Exploring the API
        - Getting oandapy – the OANDA REST API wrapper
        - Getting and parsing rates data
        - Sending an order
    - Building a trend-following forex trading platform
        - Setting up the main program
        Handling events
        - - Implementing the trend-following algorithm
        - Tracking our positions
    - VaR for risk management
    - Summary
9. Backtesting
    - An introduction to backtesting
        - Concerns in backtesting
        - Concept of an event-driven backtesting system
    - Designing and implementing a backtesting system
        - The TickData class
        - The MarketData class
        - The MarketDataSource class
        - The Order class
        - The Position class
        - The Strategy class
        - The MeanRevertingStrategy class
        - The Backtester class
        - Running our backtesting system
        - Improving your backtesting system
    - Ten considerations for a backtesting model
        - Resources restricting your model
        - Criteria of evaluation of the model
        - Estimating the quality of backtest parameters
        - Be prepared to face model risk
        - Performance of a backtest with in-sample data
        - Addressing common pitfalls in backtesting
        - Have a common sense idea of your model
        - Understanding the context for the model
        - Make sure you have the right data
        - Data mine your results
    - Discussion of algorithms in backtesting
        - K-means clustering
        - K-nearest neighbor machine learning algorithm
        - Classification and regression tree analysis
        - The 2k factorial design
        - The genetic algorithm
    - Summary
10. Excel with Python
    - Overview of COM
    - Excel for finance
    - Building a COM server
        - Prerequisites
        - Getting the pythoncom module
        - Building the Black-Scholes model COM server
        - Registering and unregistering the COM server
        - Building the Cox-Ross-Rubinstein binomial tree model COM server
        - Building the trinomial lattice model COM server
    - Building the COM client in Excel
        - Setting up the VBA code
        - Setting up the cells
    - What else can I do with COM?
    - Summary
