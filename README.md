# poem-vector

poem-vector项目分为两个模型，一个是使用构建静态词向量的经典算法word2vec训练得到的，即三个model.bin文件

此外，BERT模型一般用来构建动态词向量，但我们可以抽取BERT模型的最后一层输出（hidden states）作为静态词向量，只是这种做法得到的静态词向量实际体验不一定赶得上word2vec，由于文件超出1GitHub限制，传到了Google drive上：https://drive.google.com/file/d/1XIh4Dm-v5WfYWBk-yNQVkWVFhT_30cUC/view?usp=drive_link

两个模型都在搜韵的诗词语料上训练而成，因此仅适用于诗词相关领域。
