# CALLMSAE
Cascading Large Language Models for Salient Event Graph Generation (preprint)


## Step One

Initialize the directories

```
sh init_dir.sh
```

## Step Two

Save the NYT dataset as ```NYT_annotated``` in the directory. Run the following command

```
python get_nyt_data
```

## Step Three

```
python get_salient_events.py
```

## Step Four

```
python event_relation_prompting.py
```

For the fine-tunning code please refer to [Set-Aligning-Event-Temporal-Graph-Generation](https://github.com/Xingwei-Tan/Set-Aligning-Event-Temporal-Graph-Generation)
