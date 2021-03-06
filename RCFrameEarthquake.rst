.. include:: sub.txt

===============================================
 Reinforced Concrete Frame Earthquake Analysis
===============================================


#. The source code is shown below, which can be downloaded :download:`here <RCFrameEarthquake.py>`.
#. The file for gravity analysis is also needed :download:`here <RCFrameGravity.py>`.
#. The ReadRecord is a useful python function for parsing the PEER strong motion data base files and returning the ``dt``, ``nPts`` and creating a file containing just data points. The function is kept in a seperate file  :download:`here <ReadRecord.py>` and is imported in the example.
#. The ground motion data file :download:`here <elCentro.at2>` must be put in the same folder.
#. Change the line 9 below to set the right path where the OpenSeesPy library located.
#. Run the source code in your favorate Python program and should see ``Passed!`` in the results and a plotting of displacement for node 3

.. image:: _static/RCFrameEarthquake.png

.. literalinclude:: RCFrameEarthquake.py
   :linenos:
   :emphasize-lines: 9
