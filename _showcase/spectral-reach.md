---
show: true
width: 12
date: 2026-06-06 00:00:00 +0200
---

<div class="p-4">
    <h3>Spectral Reach — why bigger language models perform better</h3>
    <hr/>
    <div class="row align-items-center">
        <div class="col-md-7">
            <p>
                Why do bigger language models perform better?
                In our new <a href="https://icml.cc/" target="_blank">ICML 2026</a> paper, we found an explanation.
            </p>
            <p>
                We analyze language model pre-training and find that as models get larger, they can learn from
                progressively <em>weaker</em> signals: patterns in the data too faint for smaller models to pick up.
            </p>
            <p>
                You can see it in the figure to the right (bottom panel). As training proceeds (compute grows),
                large models reach lower <em>spectral position</em>. Spectral position is the measure we
                introduce. It reads off the strength of the signal a model is currently learning from,
                and can be applied at scale.
            </p>
            <p>
                Theories of learning are usually developed on toy models. I believe diagnostics that scale
                to real ones are how we get a theory that explains practice.
            </p>
        </div>
        <div class="col-md-5">
            <img src="/assets/images/covers/spectral-position.png" alt="Spectral position vs compute" class="w-100 rounded-sm">
        </div>
    </div>
    <p class="small text-muted mt-3 mb-1">
        Joint work with Jonas Scheunemann, Sven Krippendorf, Samuel Tovey, and Christian Holm.
    </p>
    <p class="mb-0">
        <a href="https://github.com/zincware/perspic" target="_blank"><i class="fab fa-github"></i> Code for spectral position</a>
        &nbsp;·&nbsp;
        <a href="https://arxiv.org/abs/2605.31244" target="_blank"><i class="fas fa-book"></i> Paper</a>
    </p>
</div>
