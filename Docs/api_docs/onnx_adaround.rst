:orphan:

.. _api-onnx-adaround:

==================================
AIMET ONNX AdaRound API
==================================

User Guide Link
================
To learn more about this technique, please see :ref:`AdaRound<ug-adaround>`

Top-level API
=============
.. autofunction:: aimet_onnx.adaround.adaround_weight.Adaround.apply_adaround


Adaround Parameters
===================
.. autoclass:: aimet_onnx.adaround.adaround_weight.AdaroundParameters
    :members:


Code Example - Adaptive Rounding (AdaRound)
===========================================

This example shows how to use AIMET to perform Adaptive Rounding (AdaRound).

**Required imports**

.. literalinclude:: ../onnx_code_examples/adaround.py
    :language: python
    :lines: 41-42

**User should write this function to pass calibration data**


.. literalinclude:: ../onnx_code_examples/adaround.py
   :language: python
   :pyobject: pass_calibration_data


**Apply Adaround**

.. literalinclude:: ../onnx_code_examples/adaround.py
    :language: python
    :pyobject: apply_adaround_example
