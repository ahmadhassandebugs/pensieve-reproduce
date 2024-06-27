# Pensieve Reproduce

## Setup

Set up conda env

```bash
conda create -n venev_tf1 pyhton=2.7
conda activate
```

Install dependencies

```bash
pip install tensorflow==1.1.0
pip install tflearn==0.3.1
```

## Run

```bash
python get_video_sizes.py
python multi_agent.py
```
