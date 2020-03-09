## DCMN
### How to Run

```
python dcmn.py  \
  --data_dir $DATA_DIR$ \
  --output_dir $OUTPUT_DIR$ \
  --train_file $TRAIN_FILE$ \
  --test_file $TEST_FILE$ \
  --output_file $OUTPUT_FILE$ \
  --fp16
```
### Apex
Please use an earlier commit of Apex - [NVIDIA/apex@4a8c4ac](https://github.com/NVIDIA/apex/commit/4a8c4ac088b6f84a10569ee89db3a938b48922b4)

### How to Cite
If you extend or use this work, please cite the [paper][paper] where it was introduced:

```
@inproceedings{dcmn,
    title={DCMN+: Dual Co-Matching Network for Multi-choice Reading Comprehension},
    author={Shuailiang Zhang and Hai Zhao and Yuwei Wu and Zhuosheng Zhang and Xi Zhou and Xiang Zhou},
    year={2020},
    booktitle = "{The Thirty-Fourth AAAI Conference on Artificial Intelligence (AAAI)}",
}
```

[paper]: https://arxiv.org/abs/1908.11511
