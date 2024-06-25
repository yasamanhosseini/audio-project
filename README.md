# audio-project
The audio project describes the preprocessing steps for environmental sound detection using a Python-based co-design approach on the Google Colab computing platform. The dataset includes ESC-50 and UrbanSound8k; ESC-50 is provided in the project link, and UrbanSound8k can be accessed using the following code:
import soundata

dataset = soundata.initialize('urbansound8k')
dataset.download()  # download the dataset
dataset.validate()  # validate that all the expected files are there

example_clip = dataset.choice_clip()  # choose a random example clip
print(example_clip)  # see the available data
