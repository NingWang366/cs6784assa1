# cs6784assa1

Suggested Python: 3.9.13

## Reproducibility Steps

### Step 1: Download this repo and cd to it

```
git clone https://github.com/NingWang366/cs6784assa1
cd cs6784assa1
```

### Step 2: Install dependencies

```
sudo apt-get update
sudo apt-get install virtualenv
virtualenv venv
source ./venv/bin/activate 

pip install -r requirements.txt
```

### Step 3: Generate all plots

```
bash reproduce.sh
```

The plots generated after running the code are present in reproducibility/freshRuns/ folder. Please go over reproducibility/readme.pdf to interpret the results.


### (Optional) Step 4: Reproduce individual plots

```
cd reproducibility/scripts/

```
