Klio Audio
==========

:release:`latest release`: |klio-audio-version| (:doc:`What's new? <changelog>`)

.. include:: /.current_status.rst

.. include:: ../../../../audio/README.rst
    :start-after: start-klio-audio-intro
    :end-before: end-klio-audio-intro

.. admonition:: Installation
    :class: tip

    To make use of ``klio-audio``, add ``klio[audio]`` in your ``job-requirements.txt`` file so that it is installed in your job's Docker image.

.. include:: ../../../../audio/README.rst
    :start-after: start-klio-audio-install

.. toctree::
   :maxdepth: 1
   :hidden:

   api/decorators
   api/io
   api/audio
   changelog

----


``klio_audio.decorators`` Module
---------------------------------

.. currentmodule:: klio_audio.decorators

.. autosummary::
    :nosignatures:

    handle_binary


``klio_audio.transforms.audio`` Module
--------------------------------------

.. currentmodule:: klio_audio.transforms.audio

.. autosummary::
    :nosignatures:

    LoadAudio
    GetSTFT
    GetSpec
    GetMelSpec
    GetMFCC
    SpecToPlot
    MelSpecToPlot
    MFCCToPlot
    WaveformToPlot


``klio_audio.transforms.io`` Module
-----------------------------------

.. currentmodule:: klio_audio.transforms.io

.. autosummary::
    :nosignatures:

    GcsLoadBinary
    GcsUploadPlot
