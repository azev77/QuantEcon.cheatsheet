.. raw:: html

	<style type="text/css">.menu>li.statistics-on>a {border-color:#444;cursor: default;}</style>

Statistics cheatsheet
=====================

Plotting
--------

.. container:: multilang-table

    +--------------+-----------------------+-------------------------------+---------------------+
    |  Operation   |         STATA         |             Pandas            |        Base R       |
    +==============+=======================+===============================+=====================+
    |              | .. code-block:: stata | .. code-block:: python        | .. code-block:: r   |
    | Scatter plot |                       |                               |                     |
    |              |     plot x y          |     df.plot.scatter('x', 'y') |   plot(df$x, df$y)  |
    |              |                       |                               |                     |
    |              |                       |                               |                     |
    |              |                       |                               |                     |
    |              |                       |                               |                     |
    +--------------+-----------------------+-------------------------------+---------------------+
    |              | .. code-block:: stata | .. code-block:: python        | .. code-block:: r   |
    | Line plot    |                       |                               |                     |
    |              |     line x y          |     df.plot('x', 'y')         |   lines(df$x, df$y) |
    |              |                       |                               |                     |
    |              |                       |                               |                     |
    |              |                       |                               |                     |
    |              |                       |                               |                     |
    +--------------+-----------------------+-------------------------------+---------------------+
    |              | .. code-block:: stata | .. code-block:: python        | .. code-block:: r   |
    |              |                       |                               |                     |
    | Histogram    |     hist x            |     df.hist('x')              |    hist(df$x)       |
    +--------------+-----------------------+-------------------------------+---------------------+
    |              | .. code-block:: stata | .. code-block:: python        | .. code-block:: r   |
    |              |                       |                               |                     |
    | Boxplot      |     graph box x       |     df.boxplot('x')           |    boxplot(df$x)    |
    +--------------+-----------------------+-------------------------------+---------------------+
