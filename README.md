# pretrainKT
pretain question_embedding with KT

## Dataset

- ### DKT-pretaining

    - assist2009---sq_len=256--sq_space=5--total_skill: shuffle--sq_skill_len=101

    - assist2012---sq_len=256--sq_space=10--total_skill: shuffle--sq_skill_len=198

    - assistEdnet---sq_len=256--sq_space=30--total_skill: shuffle--sq_skill_len=188

- ### DKVMN-pretaining

    - assist2009---sq_len=20--sq_space=5--total_skill: shuffle--sq_skill_len=101

    - assist2012---sq_len=20--sq_space=30--total_skill: shuffle--sq_skill_len=198

    - assistEdnet---sq_len=20--sq_space=30--total_skill: shuffle--sq_skill_len=188

## pretrain log
- log_2009: epoch:  390, test_auc: 2056.470
- log_2012: epoch:  390, test_auc: 33026.344
- log_ednet: epoch:  390, test_auc: 8240.736