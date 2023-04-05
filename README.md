# ChatGPT
# 方法

* [手把手教你注册ChatGPT](https://github.com/xxh2000/MyChatGPT/blob/main/%E6%95%99%E7%A8%8B/ChatGPT%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B.pdf)
* [ChatGPT Plus充值教程](https://github.com/xxh2000/MyChatGPT/blob/main/%E6%95%99%E7%A8%8B/ChatGPT%20Plus%E6%B3%A8%E5%86%8C%E6%95%99%E7%A8%8B.md)

# 论文

* [**通用人工智能火花：GPT-4早期试验-中文版本.pdf**](https://github.com/xxh2000/MyChatGPT/blob/main/pdf/%E9%80%9A%E7%94%A8%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E7%81%AB%E8%8A%B1%EF%BC%9AGPT-4%E6%97%A9%E6%9C%9F%E8%AF%95%E9%AA%8C-%E4%B8%AD%E6%96%87%E7%89%88%E6%9C%AC.pdf)

* [**通用人工智能火花：GPT-4早期试验-英文版.pdf**](https://github.com/xxh2000/MyChatGPT/blob/main/pdf/%E9%80%9A%E7%94%A8%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E7%81%AB%E8%8A%B1%EF%BC%9AGPT-4%E6%97%A9%E6%9C%9F%E8%AF%95%E9%AA%8C-%E8%8B%B1%E6%96%87%E7%89%88.pdf)

* [**Attention Is All You Need.pdf**](https://github.com/xxh2000/MyChatGPT/blob/main/pdf/Attention%20Is%20All%20You%20Need.pdf)

  > 摘要: 占主导地位的序列转导模型是基于复杂的递归或卷积神经网络，包括一个编码器和一个解码器。性能最好的模型还通过注意机制将编码器和解码器连接起来。我们提出了一个新的简单的网络结构–Transformer，它只基于注意力机制，完全不需要递归和卷积。在两个机器翻译任务上的实验表明，这些模型在质量上更胜一筹，同时也更容易并行化，需要的训练时间也大大减少。我们的模型在WMT 2014英德翻译任务中达到了28.4 BLEU，比现有的最佳结果（包括合集）提高了2 BLEU以上。在WMT 2014英法翻译任务中，我们的模型在8个GPU上训练了3.5天后，建立了新的单模型最先进的BLEU得分，即41.0分，这只是文献中最佳模型的训练成本的一小部分。

* [**Language Models are Few-Shot Learners.pdf**](https://github.com/xxh2000/MyChatGPT/blob/main/pdf/Language%20Models%20are%20Few-Shot%20Learners.pdf)

  > 摘要: 最近的工作表明，在许多NLP任务和基准上，通过对大型文本语料库进行预训练，然后对特定的任务进行微调，可以获得巨大的收益。虽然在结构上通常是任务无关的，但这种方法仍然需要特定任务的微调数据集，包括几千或几万个例子。相比之下，人类通常只需通过几个例子或简单的指令就能完成一项新的语言任务–而目前的NLP系统在很大程度上仍难以做到这一点。在这里，我们展示了扩大语言模型的规模，大大改善了与任务无关的、少量的性能，有时甚至达到了与之前最先进的微调方法的竞争力。具体来说，我们训练了GPT-3，一个具有1750亿个参数的自回归语言模型，比以前的任何非稀疏语言模型多10倍，并测试了它在少数情况下的性能。对于所有的任务，GPT-3的应用没有任何梯度更新或微调，纯粹通过与模型的文本互动来指定任务和少量演示。GPT-3在许多NLP数据集上取得了强大的性能，包括翻译、回答问题和cloze任务，以及一些需要即时推理或领域适应的任务，如解读单词、在句子中使用一个新词或进行3位数的算术。同时，我们也发现了一些数据集，在这些数据集中，GPT-3的几率学习仍然很困难，还有一些数据集，GPT-3面临着与大型网络语料库训练有关的方法学问题。最后，我们发现，GPT-3可以生成人类评价者难以区分的新闻文章样本。我们讨论了这一发现和GPT-3总体上的更广泛的社会影响

* [**Training language models to follow instructions with human feedback.pdf**](https://github.com/xxh2000/MyChatGPT/blob/main/pdf/Training%20language%20models%20to%20follow%20instructions%20with%20human%20feedback.pdf)

  > 摘要: 让语言模型变得更大并不意味着它们能更好地遵循用户的意图。例如，大型语言模型可以产生不真实的、有毒的或根本对用户没有帮助的输出。换句话说，这些模型没有与用户保持一致。在本文中，我们展示了一个途径，通过人类反馈的微调，在广泛的任务中使语言模型与用户的意图保持一致。从一组标签员写的提示语和通过OpenAI API提交的提示语开始，我们收集了一组标签员演示的所需模型行为的数据集，我们利用监督学习对GPT-3进行微调。然后，我们收集模型输出的排名数据集，我们利用人类反馈的强化学习来进一步微调这个监督模型。我们把产生的模型称为InstructGPT。在人类对我们的提示分布的评估中，尽管参数少了100倍，但1.3B参数的InstructGPT模型的输出比175B的GPT-3的输出更受欢迎。此外，InstructGPT模型显示了真实性的改善和有毒输出生成的减少，同时在公共NLP数据集上的性能回归最小。尽管InstructGPT仍然会犯一些简单的错误，但我们的结果表明，利用人类反馈进行微调是使语言模型与人类意图相一致的一个有希望的方向。

* [**Pre-train, Prompt, and Predict A Systematic Survey of Prompting Methods in Natural Language Processing.pdf**](https://github.com/xxh2000/MyChatGPT/blob/main/pdf/Pre-train%2C%20Prompt%2C%20and%20Predict%20A%20Systematic%20Survey%20of%20Prompting%20Methods%20in%20Natural%20Language%20Processing.pdf)

  > 摘要：ChatGPT 训练时的输入使用的是 Prompt，Prompt 是研究者们为了下游任务设计出来的一种输入形式或模板，它能够帮助预训练模型“回忆”起自己在预训练时“学习”到的东西。

