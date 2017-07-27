# model compression

* [Compression of Neural Machine Translation Models via Pruning](https://github.com/NEU-NLPLAB/neu_nlplab_learning/blob/master/paper/NMT/model%20compression/2016-ACL-CompressionofNeuralMachineTranslationModelsviaPruning.pdf)

  论文中针对神经网络中存在的参数冗余问题提出了几种不同的剪枝策略。在NMT任务中发现，当裁剪40%的网络参数时，新模型性能几乎不受影响。
  当裁剪80%的网络参数时，通过重训练，新模型性能能恢复甚至超过原有模型。<br> 
  推荐人：吴开心
-----
* [Sequence-Level Knowledge Distillation](https://github.com/NEU-NLPLAB/neu_nlplab_learning/blob/master/paper/NMT/model%20compression/2016-ACL-Sequence-Level%20Knowledge%20Distillation.pdf)

  论文中采用了知识精炼的方法来缩减传统NMT的网络结构。
  核心思想就是用一个小网络（student network）来模拟一个事先训练好的大网络（teacher network）。<br>
  推荐人：吴开心
-----
