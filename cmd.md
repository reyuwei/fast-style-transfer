python evaluate.py --checkpoint checkpoints/fns.ckpt --in-path examples/content --out-path examples/results109 --allow-different-dimensions

python style.py --style examples/style_xiula/xiula_circus.JPG --content-weight 1.5e1 --checkpoint-iterations 1000 --batch-size 20 --checkpoint-dir checkpoints