|BuildStatus|_ |PyPiVersion|_ |PythonSupport|_

.. |BuildStatus| image:: https://github.com/interpretml/dice/workflows/Python%20package/badge.svg
.. _BuildStatus: https://github.com/interpretml/dice/actions?query=workflow%3A%22Python+package%22

.. |PyPiVersion| image:: https://img.shields.io/pypi/v/dice-ml
.. _PyPiVersion: https://pypi.org/project/dice-ml/

.. |PythonSupport| image:: https://img.shields.io/pypi/pyversions/dice-ml
.. _PythonSupport: https://pypi.org/project/dice-ml/

Multi-objective Optimization for Counterfactual Explanation with Structural Causal Model
======================================================================

*Our work pay attention to counterfactual explanation with the structural causal model and multiobjective optimization*

Author: `Dung Duong <https://scholar.google.com/citations?user=hoq2nt8AAAAJ&hl=en>`_, `Qian Li <https://scholar.google.com/citations?hl=en&user=yic0QMYAAAAJ>`_, `Guandong Xu <https://scholar.google.com/citations?user=kcrdCq4AAAAJ&hl=en&oi=ao>`_

This is the code used for the paper `Prototype-based Counterfactual Explanation for Causal Classification <https://arxiv.org/abs/2105.00703>`_. I submitted this paper to IJCAI 2021 and got rejected. This work is still in progress. I appreciate your feedback to improve my work. Contact me at TriDung.Duong@student.uts.edu.au


How to run
-------------------------
Train auto-encoder model

.. code-block:: console

	python /home/trduong/Data/multiobj-scm-cf/src/ml_cfexplainer/run_algorithm/dfencoder_adult.py
	python /home/trduong/Data/multiobj-scm-cf/src/ml_cfexplainer/run_algorithm/dfencoder_adult.py


Reproduce the result

.. code-block:: console

	python /multiobj-scm-cf/src/run_simplebn.py
	python /multiobj-scm-cf/src/run_adult.py
	python /multiobj-scm-cf/src/run_credit.py
	python /multiobj-scm-cf/src/run_sangiovese.py


Code Structure 
-------------------------


Citing
-------------------------
If you find our work useful for your research work, please cite it as follows.


Reference:
-------------------------

- Mahajan, D., Tan, C., & Sharma, A. (2019). Preserving causal constraints in counterfactual explanations for machine learning classifiers. arXiv preprint arXiv:1912.03277.
- Van Looveren, A., & Klaise, J. (2019). Interpretable counterfactual explanations guided by prototypes. arXiv preprint arXiv:1907.02584.