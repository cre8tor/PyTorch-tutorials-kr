파이토치(PyTorch) 튜토리얼에 오신 것을 환영합니다
===================================================

PyTorch를 어떻게 사용하는지 알고 싶다면 시작하기(Getting Started) 튜토리얼부터 시작해보세요.
:doc:`/beginner/deep_learning_60min_blitz` 가 가장 일반적인 출발점으로, 심층
신경망(deep neural network)을 구축할 때 PyTorch를 어떻게 사용하는지에 대한
전반적인 내용을 기본부터 제공합니다.

(역자 주: 한국어 번역에 대한 오타나 오역을 발견하시면
`번역 저장소 <https://github.com/9bow/PyTorch-tutorials-kr>`__ 에
`이슈 <https://github.com/9bow/PyTorch-tutorials-kr/issues/new>`__ 또는
`PR <https://github.com/9bow/PyTorch-tutorials-kr/pulls>`__ 을 남겨주세요.)

Some considerations:

* We’ve added a new feature to tutorials that allows users to open the notebook associated with a tutorial in Google Colab.
  Visit `this page <https://pytorch.org/tutorials/beginner/colab.html>`_ for more information.
* If you would like to do the tutorials interactively via IPython / Jupyter,
  each tutorial has a download link for a Jupyter Notebook and Python source code.
* Additional high-quality examples are available, including image classification,
  unsupervised learning, reinforcement learning, machine translation, and
  many other applications, in `PyTorch Examples
  <https://github.com/pytorch/examples/>`_.
* You can find reference documentation for the PyTorch API and layers in `PyTorch Docs
  <https://pytorch.org/docs>`_ or via inline help.
* If you would like the tutorials section improved, please open a github issue
  `here <https://github.com/pytorch/tutorials>`_ with your feedback.
* Check out our
  `PyTorch Cheat Sheet <https://pytorch.org/tutorials/beginner/ptcheat.html>`_
  for additional useful information.
* Finally, here's a link to the
  `PyTorch Release Notes <https://github.com/pytorch/pytorch/releases>`_

시작하기 (Getting Started)
---------------------------

.. customgalleryitem::
   :figure: /_static/img/thumbnails/pytorch-logo-flat.png
   :tooltip: Understand PyTorch’s Tensor library and neural networks at a high level
   :description: :doc:`/beginner/deep_learning_60min_blitz`

.. customgalleryitem::
   :figure: /_static/img/thumbnails/landmarked_face2.png
   :tooltip: Learn how to load and preprocess/augment data from a non trivial dataset
   :description: :doc:`/beginner/data_loading_tutorial`

.. customgalleryitem::
   :tooltip: This tutorial introduces the fundamental concepts of PyTorch through self-contained examples
   :figure: /_static/img/thumbnails/examples.png
   :description: :doc:`/beginner/pytorch_with_examples`

.. customgalleryitem::
   :figure: /_static/img/thumbnails/sphx_glr_transfer_learning_tutorial_001.png
   :tooltip: In transfer learning, a model created from one task is used in another
   :description: :doc:`beginner/transfer_learning_tutorial`

.. customgalleryitem::
   :figure: /_static/img/thumbnails/floppy.png
   :tooltip: Explore use cases for the saving and loading of PyTorch models
   :description: :doc:`beginner/saving_loading_models`

.. .. galleryitem:: beginner/saving_loading_models.py

.. customgalleryitem::
   :figure: /_static/img/thumbnails/pytorch_tensorboard.png
   :tooltip: Learn to use TensorBoard to visualize data and model training
   :description: :doc:`intermediate/tensorboard_tutorial`

.. customgalleryitem::
   :figure: /_static/img/torch.nn.png
   :tooltip: Use torch.nn to create and train a neural network
   :description: :doc:`beginner/nn_tutorial`


.. raw:: html

    <div style='clear:both'></div>


이미지 (Image)
----------------------

.. customgalleryitem::
   :figure: /_static/img/thumbnails/tv-img.png
   :tooltip: Finetuning a pre-trained Mask R-CNN model
   :description: :doc:`intermediate/torchvision_tutorial`

.. customgalleryitem::
   :figure: /_static/img/thumbnails/eye.png
   :tooltip: Finetune and feature extract the torchvision models
   :description: :doc:`beginner/finetuning_torchvision_models_tutorial`

.. customgalleryitem::
   :figure: /_static/img/stn/Five.gif
   :tooltip: Learn how to augment your network using a visual attention mechanism called spatial transformer networks
   :description: :doc:`intermediate/spatial_transformer_tutorial`

.. customgalleryitem::
   :figure: /_static/img/neural-style/sphx_glr_neural_style_tutorial_004.png
   :tooltip: How to implement the Neural-Style algorithm developed by Gatys, Ecker, and Bethge
   :description: :doc:`advanced/neural_style_tutorial`

.. customgalleryitem::
   :figure: /_static/img/panda.png
   :tooltip: Raise your awareness to the security vulnerabilities of ML models, and get insight into the hot topic of adversarial machine learning
   :description: :doc:`beginner/fgsm_tutorial`

.. customgalleryitem::
   :figure: /_static/img/cat.jpg
   :tooltip: Exporting a Model from PyTorch to ONNX and Running it using ONNXRuntime
   :description: :doc:`advanced/super_resolution_with_onnxruntime`

.. raw:: html

    <div style='clear:both'></div>


오디오 (Audio)
----------------------

.. customgalleryitem::
   :figure: /_static/img/audio_preprocessing_tutorial_waveform.png
   :tooltip: Preprocessing with torchaudio Tutorial
   :description: :doc:`beginner/audio_preprocessing_tutorial`

.. raw:: html

    <div style='clear:both'></div>


텍스트 (Text)
----------------------

.. customgalleryitem::
   :figure: /_static/img/chat.png
   :tooltip: Train a simple chatbot using movie scripts
   :description: :doc:`beginner/chatbot_tutorial`

.. customgalleryitem::
   :figure: /_static/img/char_rnn_generation.png
   :tooltip: Generate names from languages
   :description: :doc:`intermediate/char_rnn_generation_tutorial`

.. customgalleryitem::
   :figure: /_static/img/rnnclass.png
   :tooltip: Build and train a basic character-level RNN to classify words
   :description: :doc:`intermediate/char_rnn_classification_tutorial`

.. customgalleryitem::
    :tooltip: Explore the key concepts of deep learning programming using Pytorch
    :figure: /_static/img/thumbnails/babel.jpg
    :description: :doc:`/beginner/deep_learning_nlp_tutorial`

.. galleryitem:: intermediate/seq2seq_translation_tutorial.py
  :figure: _static/img/seq2seq_flat.png

.. customgalleryitem::
    :tooltip: Sentiment Ngrams with Torchtext
    :figure: /_static/img/text_sentiment_ngrams_model.png
    :description: :doc:`/beginner/text_sentiment_ngrams_tutorial`

.. raw:: html

    <div style='clear:both'></div>

생성 모델 (Generative)
----------------------

.. customgalleryitem::
    :tooltip: Train a generative adversarial network (GAN) to generate new celebrities
    :figure: /_static/img/dcgan_generator.png
    :description: :doc:`beginner/dcgan_faces_tutorial`

.. raw:: html

    <div style='clear:both'></div>


강화 학습 (Reinforcement Learning)
------------------------------------------------------------

.. customgalleryitem::
    :tooltip: Use PyTorch to train a Deep Q Learning (DQN) agent
    :figure: /_static/img/cartpole.gif
    :description: :doc:`intermediate/reinforcement_q_learning`

.. raw:: html

    <div style='clear:both'></div>

PyTorch 확장하기 (Extending PyTorch)
------------------------------------------------------------

.. customgalleryitem::
    :tooltip: Create extensions using numpy and scipy
    :figure: /_static/img/scipynumpy.png
    :description: :doc:`advanced/numpy_extensions_tutorial`

.. customgalleryitem::
   :tooltip: Implement custom extensions in C++ or CUDA for eager PyTorch
   :description: :doc:`/advanced/cpp_extension`
   :figure: _static/img/cpp_logo.png

.. customgalleryitem::
   :tooltip: Implement custom operators in C++ or CUDA for TorchScript
   :description: :doc:`/advanced/torch_script_custom_ops`
   :figure: _static/img/cpp_logo.png


.. raw:: html

    <div style='clear:both'></div>


운영환경에서 사용 (Production Usage)
------------------------------------------------------------

.. customgalleryitem::
   :tooltip: Introduction to TorchScript
   :description: :doc:`beginner/Intro_to_TorchScript_tutorial`
   :figure: _static/img/torchscript.png

.. customgalleryitem::
   :figure: /_static/img/torchscript.png
   :tooltip: Experiment with some of the key features of the TorchScript
   :description: :doc:`beginner/deploy_seq2seq_hybrid_frontend_tutorial`

.. customgalleryitem::
   :tooltip: Loading a PyTorch model in C++
   :description: :doc:`advanced/cpp_export`
   :figure: _static/img/cpp_logo.png

.. customgalleryitem::
   :tooltip: Parallelize computations across processes and clusters of machines
   :description: :doc:`/intermediate/dist_tuto`
   :figure: _static/img/distributed/DistPyTorch.jpg

.. customgalleryitem::
  :tooltip: Train large models with multiple GPUs using model parallel
  :description: :doc:`/intermediate/model_parallel_tutorial`
  :figure: _static/img/distributed/DistPyTorch.jpg

.. customgalleryitem::
  :tooltip: Getting started with DistributedDataParallel
  :description: :doc:`/intermediate/ddp_tutorial`
  :figure: _static/img/distributed/DistPyTorch.jpg

.. customgalleryitem::
   :tooltip: PyTorch distributed trainer with Amazon AWS
   :description: :doc:`/beginner/aws_distributed_training_tutorial`
   :figure: _static/img/distributed/DistPyTorch.jpg


.. raw:: html

    <div style='clear:both'></div>


다른 언어에서의 PyTorch (PyTorch in Other Languages)
------------------------------------------------------------

.. customgalleryitem::
    :tooltip: Using the PyTorch C++ Frontend
    :figure: /_static/img/cpp-pytorch.png
    :description: :doc:`advanced/cpp_frontend`

.. raw:: html

    <div style='clear:both'></div>

.. -----------------------------------------
.. Page TOC
.. -----------------------------------------
.. toctree::
   :maxdepth: 2
   :hidden:
   :includehidden:
   :caption: 시작하기 (Getting Started)

   beginner/deep_learning_60min_blitz
   beginner/data_loading_tutorial
   beginner/pytorch_with_examples
   beginner/transfer_learning_tutorial
   beginner/deploy_seq2seq_hybrid_frontend_tutorial
   intermediate/tensorboard_tutorial
   beginner/saving_loading_models
   beginner/nn_tutorial
   beginner/Intro_to_TorchScript_tutorial

.. toctree::
   :maxdepth: 2
   :includehidden:
   :hidden:
   :caption: 이미지 (Image)

   intermediate/torchvision_tutorial
   beginner/finetuning_torchvision_models_tutorial
   intermediate/spatial_transformer_tutorial
   advanced/neural_style_tutorial
   beginner/fgsm_tutorial
   advanced/super_resolution_with_onnxruntime

.. toctree::
   :maxdepth: 2
   :includehidden:
   :hidden:
   :caption: 오디오 (Audio)

   beginner/audio_preprocessing_tutorial

.. toctree::
   :maxdepth: 2
   :includehidden:
   :hidden:
   :caption: 텍스트 (Text)

   beginner/chatbot_tutorial
   intermediate/char_rnn_generation_tutorial
   intermediate/char_rnn_classification_tutorial
   beginner/deep_learning_nlp_tutorial
   intermediate/seq2seq_translation_tutorial
   beginner/text_sentiment_ngrams_tutorial

.. toctree::
   :maxdepth: 2
   :includehidden:
   :hidden:
   :caption: 생성 모델

   beginner/dcgan_faces_tutorial

.. toctree::
   :maxdepth: 2
   :includehidden:
   :hidden:
   :caption: 강화 학습

   intermediate/reinforcement_q_learning

.. toctree::
   :maxdepth: 2
   :includehidden:
   :hidden:
   :caption: PyTorch 확장하기

   advanced/numpy_extensions_tutorial
   advanced/cpp_extension
   advanced/torch_script_custom_ops

.. toctree::
   :maxdepth: 2
   :includehidden:
   :hidden:
   :caption: 운영환경에서 사용

   intermediate/model_parallel_tutorial
   intermediate/ddp_tutorial
   intermediate/dist_tuto
   intermediate/flask_rest_api_tutorial
   beginner/aws_distributed_training_tutorial
   advanced/cpp_export

.. toctree::
   :maxdepth: 2
   :includehidden:
   :hidden:
   :caption: 다른 언어에서의 PyTorch

   advanced/cpp_frontend
