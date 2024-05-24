🔧 Contrib
===============

Experimental features and algorithms that don't meet the
:ref:`inclusion_criteria`.

.. currentmodule:: optax.contrib

.. autosummary::
    cocob
    COCOBState
    dadapt_adamw
    DAdaptAdamWState
    differentially_private_aggregate
    DifferentiallyPrivateAggregateState
    dog
    DoGState
    dowg
    DoWGState
    dpsgd
    mechanize
    MechanicState
    momo
    MomoState
    momo_adam
    MomoAdamState
    prodigy
    ProdigyState
    sam
    SAMState
    schedule_free
    schedule_free_eval_params
    ScheduleFreeState
    split_real_and_imaginary
    SplitRealAndImaginaryState
    sophia
    scale_by_sophia
    SophiaState

Complex-valued Optimization
~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. autofunction:: split_real_and_imaginary
.. autoclass:: SplitRealAndImaginaryState

Continuous coin betting
~~~~~~~~~~~~~~~~~~~~~~~
.. autofunction:: cocob
.. autoclass:: COCOBState

D-adaptation
~~~~~~~~~~~~
.. autofunction:: dadapt_adamw
.. autoclass:: DAdaptAdamWState

Differentially Private Aggregate
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. autofunction:: differentially_private_aggregate
.. autoclass:: DifferentiallyPrivateAggregateState
.. autofunction:: dpsgd

Distance over Gradients
~~~~~~~~~~~~~~~~~~~~~~~
.. autofunction:: dog
.. autoclass:: DoGState
.. autofunction:: dowg
.. autoclass:: DoWGState

Mechanize
~~~~~~~~~
.. autofunction:: mechanize
.. autoclass:: MechanicState

Momo
~~~~
.. autofunction:: momo
.. autoclass:: MomoState
.. autofunction:: momo_adam
.. autoclass:: MomoAdamState

Prodigy
~~~~~~~
.. autofunction:: prodigy
.. autoclass:: ProdigyState
    :members:

Schedule-Free
~~~~~~~~~~~~~
.. autofunction:: schedule_free
.. autofunction:: schedule_free_eval_params
.. autoclass:: ScheduleFreeState

Sharpness aware minimization
~~~~~~~~~~~~~~~~~~~~~~~~~~~~
.. autofunction:: sam
.. autoclass:: SAMState

Sophia
~~~~~~
.. autofunction:: sophia
.. autofunction:: scale_by_sophia
.. autoclass:: SophiaState
