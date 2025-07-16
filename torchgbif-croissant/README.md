# `TorchGBIF`: FAIR PyTorch DataLoaders and DataSets for GBIF data

See sample batches on <a target="_blank" href="https://colab.research.google.com/drive/1YF3mJHuz7rKIqR9VBTPqOFH8COfHp2Ym?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

Sample batches on HuggingFace: https://huggingface.co/datasets/thisistaimur/torchgbif-batches-sample

Croissant LD-JSON: https://huggingface.co/api/datasets/thisistaimur/torchgbif-batches-sample/croissant


TorchGBIF is a PyTorch library that provides FAIR (Findable, Accessible, Interoperable, Reusable) DataLoaders and DataSets for GBIF (Global Biodiversity Information Facility) data, enabling easy access to biodiversity data for machine learning tasks with research reproducibility.

GBIF is a global network and data infrastructure that provides access to data about all types of life on Earth, including species occurrence records, taxonomic information, images, audio and more.The GBIF API provides acces to this data via SQL queries, however the data itself is not in a format that can be used directly with PyTorch. TorchGBIF provides a set of DataLoaders and DataSets that can be used to easily access GBIF data in a format that is compatible with PyTorch, while automatically generating RO-Crates for FAIR research workflows.

You can the find code, tutorials and examples on: https://github.com/thisistaimur/torchgbif/tree/master

