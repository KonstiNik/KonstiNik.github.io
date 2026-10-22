---
show: true
width: 6
date: 2026-03-01 00:00:00 +0100
---

<div class="p-4">
    <h3>OpenEuroLLM: data curation for post-training</h3>
    <hr/>
    <p>
        From March to August 2026 I was a research intern at the
        <a href="https://institute-tue.ellis.eu/" target="_blank">ELLIS Institute Tübingen</a>,
        working on the post-training of <a href="https://openeurollm.eu/" target="_blank">OpenEuroLLM</a> models.
    </p>
    <ul class="pl-3">
        <li>
            Document-level data curation for supervised fine-tuning (SFT): annotated about 12M samples
            (about 80B tokens) of open post-training data with fine-tuned Qwen3 models, and used the
            annotations to merge and filter datasets.
        </li>
        <li>
            Ran SFT of thinking and instruct models with TRL on EuroHPC systems (Leonardo, LUMI,
            MareNostrum 5) to compare curation strategies. Quality filtering speeds up learning; data
            diversity is what it takes to beat the baseline.
        </li>
        <li>
            Ported models from OLMo-core to TRL and adapted Qwen3 chat templates to in-house models
            and tokenizers.
        </li>
        <li>
            Contributed SFT data preprocessing tooling and a workflow manager that lets a coding agent
            submit and monitor SLURM jobs on MareNostrum 5 under human review.
        </li>
    </ul>
    <p class="mb-0">
        <a href="https://github.com/OpenEuroLLM/post-training" target="_blank"><i class="fab fa-github"></i> Post-training code</a>
        &nbsp;·&nbsp;
        <a href="https://openeurollm.eu/" target="_blank"><i class="fas fa-globe"></i> OpenEuroLLM</a>
    </p>
</div>
