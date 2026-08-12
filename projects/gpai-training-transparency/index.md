---
title: GPAI Training Transparency
subtitle: Quality Assessment AI Act Article 53(1)(d) Public Summaries
description: |
  The [AI Act\'s Article 53(1)(d)](https://ai-act-service-desk.ec.europa.eu/en/ai-act/article-53) requires General-Purpose AI (GPAI) model providers to publish *\"a sufficiently detailed summary about the content used for training \... according to [a template](https://digital-strategy.ec.europa.eu/en/library/explanatory-notice-and-template-public-summary-training-content-general-purpose-ai-models) provided by the [AI Office](https://digital-strategy.ec.europa.eu/en/policies/ai-office)\"*. Enforcement by the AI Office has begun as of **2nd August 2026**.  To support this, we discovered [**39 public summaries**](list_summaries), which we evaluate across two aspects: <mark>Transparency</mark> and <mark>Usefulness</mark> and assign a score using [our developed methodology](methodology).
css: gpaitrainingtransparency.css
js: sorttable.js
---

> project last updated on: <date>

Our findings expose challenges
regarding accessibility, vagueness and incompleteness of information,
and limitations this poses on rightsholders. We also highlight
**missing summaries for 20 models** based on our preliminary analysis.
Please [get in touch](about) if you find any summaries or would like to
know more about our work.

> See our peer-reviewed article: Dick A. H. Blankvoort, Harshvardhan J.
Pandit, and Maximilian Gahntz (2026). ***Quality Assessment of Public
Summary of Training Content for GPAI models required by AI Act Article
53(1)(d)***. 9th ACM Conference on Fairness, Accountability, and
Transparency (FAccT), Montreal, Canada. Zenodo.
[DOI:10.1145/3805689.3806755](https://doi.org/10.1145/3805689.3806755)

## Media Coverage

- *Euractiv* \"[*AI labs at odds with EU over half-hearted data
disclosures*](https://www.euractiv.com/news/ai-labs-at-odds-with-eu-over-half-hearted-data-disclosures/)
(7 Aug 2026)\
- *Euractiv* \"[*Researchers have trouble finding AI training data
summaries*](https://www.euractiv.com/news/researchers-have-trouble-finding-ai-training-data-summaries/)
(2 Mar 2026);\
- *Tech Policy Press* \"[*How Big AI Developers are Skirting a Mandate for
Training Data
Transparency*](https://www.techpolicy.press/how-big-ai-developers-are-skirting-a-mandate-for-training-data-transparency/)
(4 Mar 2026).

## Findings

The table below shows an [overview evaluated public
summaries](#evaluations) with
[A+]{.gradeAplus}
as the highest grade score and
[F]{.gradeF}
the lowest. You can also click on the columns to sort the table by name
or by score. A separate list is provided further below with published
summaries [currently being evaluated](#WIP), and another list for models
which require a [public summary is missing](#missing) despite being
necessary. You can click the model name to go to the detailed evaluation
page which has more information, a link to the summary, and our
evaluation notes. See [detailed overview](detailed-overview) with scores
for each section of the public summary. The [list of
summaries](list_summaries) provides links to all found summaries.

### Evaluated Public Summaries

<table id="table-evaluations" class="sortable">
    <the<table id="table-evaluations" class="sortable">
  <thead>
    <tr>
      <th>Model</th>
      <th class="only-desktop">Provider</th>
      <th style="text-align: center">Transparency</th>
      <th style="text-align: center">Usefulness</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="name-cell">
        <a href="evals/apertus/" target="_blank" title="data: ">
          <u>Apertus</u>
        </a>
        <span class="only-mobile">Swiss AI Initiative</span>
      </td>
      <td class="only-desktop">Swiss AI Initiative</td>
      <td class="data-cell grade open" sorttable_customkey="92.9">A&nbsp;&nbsp;</td>
      <td class="data-cell grade open" sorttable_customkey="97.14">A+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/fibo/" target="_blank" title="data: ">
          <u>FIBO</u>
        </a>
        <span class="only-mobile">Bria AI</span>
      </td>
      <td class="only-desktop">Bria AI</td>
      <td class="data-cell grade open" sorttable_customkey="87.01">B+</td>
      <td class="data-cell grade open" sorttable_customkey="97.2">A+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/bria/" target="_blank" title="data: ">
          <u>Bria 3.2</u>
        </a>
        <span class="only-mobile">Bria AI</span>
      </td>
      <td class="only-desktop">Bria AI</td>
      <td class="data-cell grade open" sorttable_customkey="86.97">B+</td>
      <td class="data-cell grade open" sorttable_customkey="94.74">A&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/smollm3/" target="_blank" title="data: ">
          <u>SmolLM3-3B</u>
        </a>
        <span class="only-mobile">HuggingFace</span>
      </td>
      <td class="only-desktop">HuggingFace</td>
      <td class="data-cell grade open" sorttable_customkey="82.5">B+</td>
      <td class="data-cell grade open" sorttable_customkey="86.01">B+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/domyn/" target="_blank" title="data: ">
          <u>Domyn Large</u>
        </a>
        <span class="only-mobile">Domyn</span>
      </td>
      <td class="only-desktop">Domyn</td>
      <td class="data-cell grade open" sorttable_customkey="83.2">B+</td>
      <td class="data-cell grade open" sorttable_customkey="81.82">B+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/bielik/" target="_blank" title="data: ">
          <u>Bielik v3 11B Instruct</u>
        </a>
        <span class="only-mobile">SpeakLeash</span>
      </td>
      <td class="only-desktop">SpeakLeash</td>
      <td class="data-cell grade open" sorttable_customkey="89.53">B+</td>
      <td class="data-cell grade partial" sorttable_customkey="71.11">C+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/adobe-firefly/" target="_blank" title="data: ">
          <u>Adobe Firefly</u>
        </a>
        <span class="only-mobile">Adobe</span>
      </td>
      <td class="only-desktop">Adobe</td>
      <td class="data-cell grade partial" sorttable_customkey="71.79">C+</td>
      <td class="data-cell grade open" sorttable_customkey="82.38">B+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/inkling/" target="_blank" title="data: ">
          <u>Inkling</u>
        </a>
        <span class="only-mobile">Thinking Machines</span>
      </td>
      <td class="only-desktop">Thinking Machines</td>
      <td class="data-cell grade partial" sorttable_customkey="67.23">C+</td>
      <td class="data-cell grade partial" sorttable_customkey="70.77">C+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/inkling-small/" target="_blank" title="data: ">
          <u>Inkling Small</u>
        </a>
        <span class="only-mobile">Thinking Machines</span>
      </td>
      <td class="only-desktop">Thinking Machines</td>
      <td class="data-cell grade partial" sorttable_customkey="67.74">C+</td>
      <td class="data-cell grade partial" sorttable_customkey="69.93">C+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/flux-3/" target="_blank" title="data: ">
          <u>FLUX.3</u>
        </a>
        <span class="only-mobile">Black Forest Labs</span>
      </td>
      <td class="only-desktop">Black Forest Labs</td>
      <td class="data-cell grade open" sorttable_customkey="76.16">B&nbsp;&nbsp;</td>
      <td class="data-cell grade partial" sorttable_customkey="59.42">C&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/nova-2-lite/" target="_blank" title="data: ">
          <u>Nova 2 Lite</u>
        </a>
        <span class="only-mobile">Amazon</span>
      </td>
      <td class="only-desktop">Amazon</td>
      <td class="data-cell grade partial" sorttable_customkey="71.93">C+</td>
      <td class="data-cell grade partial" sorttable_customkey="62.3">C+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/fastwebmiia/" target="_blank" title="data: ">
          <u>FastwebMIIA</u>
        </a>
        <span class="only-mobile">Fastweb</span>
      </td>
      <td class="only-desktop">Fastweb</td>
      <td class="data-cell grade partial" sorttable_customkey="53.19">C&nbsp;&nbsp;</td>
      <td class="data-cell grade partial" sorttable_customkey="73.23">C+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/mai-cyber-1-flash/" target="_blank" title="data: ">
          <u>MAI Cyber 1 Flash</u>
        </a>
        <span class="only-mobile">Microsoft</span>
      </td>
      <td class="only-desktop">Microsoft</td>
      <td class="data-cell grade partial" sorttable_customkey="69.67">C+</td>
      <td class="data-cell grade partial" sorttable_customkey="50.0">C&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/minimax-m3/" target="_blank" title="data: ">
          <u>Minimax M3</u>
        </a>
        <span class="only-mobile">Minimax</span>
      </td>
      <td class="only-desktop">Minimax</td>
      <td class="data-cell grade partial" sorttable_customkey="70.06">C+</td>
      <td class="data-cell grade closed" sorttable_customkey="48.89">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/mai-code-1-flash/" target="_blank" title="data: ">
          <u>MAI Code 1 Flash</u>
        </a>
        <span class="only-mobile">Microsoft</span>
      </td>
      <td class="only-desktop">Microsoft</td>
      <td class="data-cell grade partial" sorttable_customkey="68.82">C+</td>
      <td class="data-cell grade partial" sorttable_customkey="50.0">C&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/mai-image-2_5/" target="_blank" title="data: ">
          <u>MAI-Image-2.5</u>
        </a>
        <span class="only-mobile">Microsoft</span>
      </td>
      <td class="only-desktop">Microsoft</td>
      <td class="data-cell grade partial" sorttable_customkey="71.08">C+</td>
      <td class="data-cell grade closed" sorttable_customkey="46.2">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/ministral-3-14B/" target="_blank" title="data: ">
          <u>Ministral 3 14B</u>
        </a>
        <span class="only-mobile">Mistral AI</span>
      </td>
      <td class="only-desktop">Mistral AI</td>
      <td class="data-cell grade partial" sorttable_customkey="57.93">C&nbsp;&nbsp;</td>
      <td class="data-cell grade partial" sorttable_customkey="58.93">C&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/ministral-3-3B/" target="_blank" title="data: ">
          <u>Ministral 3 3B</u>
        </a>
        <span class="only-mobile">Mistral AI</span>
      </td>
      <td class="only-desktop">Mistral AI</td>
      <td class="data-cell grade partial" sorttable_customkey="57.93">C&nbsp;&nbsp;</td>
      <td class="data-cell grade partial" sorttable_customkey="58.93">C&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/ministral-3-8B/" target="_blank" title="data: ">
          <u>Ministral 3 8B</u>
        </a>
        <span class="only-mobile">Mistral AI</span>
      </td>
      <td class="only-desktop">Mistral AI</td>
      <td class="data-cell grade partial" sorttable_customkey="57.93">C&nbsp;&nbsp;</td>
      <td class="data-cell grade partial" sorttable_customkey="58.93">C&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/mai-image-2/" target="_blank" title="data: ">
          <u>MAI-Image-2</u>
        </a>
        <span class="only-mobile">Microsoft</span>
      </td>
      <td class="only-desktop">Microsoft</td>
      <td class="data-cell grade partial" sorttable_customkey="70.12">C+</td>
      <td class="data-cell grade closed" sorttable_customkey="46.2">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/gpt-5-6-luna/" target="_blank" title="data: ">
          <u>GPT-5.6 Luna</u>
        </a>
        <span class="only-mobile">OpenAI</span>
      </td>
      <td class="only-desktop">OpenAI</td>
      <td class="data-cell grade partial" sorttable_customkey="67.76">C+</td>
      <td class="data-cell grade closed" sorttable_customkey="47.52">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/apertus-1-5/" target="_blank" title="data: ">
          <u>Apertus v1.5</u>
        </a>
        <span class="only-mobile">Swiss AI Initiative</span>
      </td>
      <td class="only-desktop">Swiss AI Initiative</td>
      <td class="data-cell grade partial" sorttable_customkey="54.24">C&nbsp;&nbsp;</td>
      <td class="data-cell grade partial" sorttable_customkey="60.99">C+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/gpt-5-5/" target="_blank" title="data: ">
          <u>GPT-5.5</u>
        </a>
        <span class="only-mobile">OpenAI</span>
      </td>
      <td class="only-desktop">OpenAI</td>
      <td class="data-cell grade partial" sorttable_customkey="67.59">C+</td>
      <td class="data-cell grade closed" sorttable_customkey="47.52">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/gemma-4/" target="_blank" title="data: ">
          <u>Gemma 4</u>
        </a>
        <span class="only-mobile">Google</span>
      </td>
      <td class="only-desktop">Google</td>
      <td class="data-cell grade partial" sorttable_customkey="59.54">C&nbsp;&nbsp;</td>
      <td class="data-cell grade partial" sorttable_customkey="53.6">C&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/gemini-3-pro/" target="_blank" title="data: ">
          <u>Gemini 3 Pro</u>
        </a>
        <span class="only-mobile">Google</span>
      </td>
      <td class="only-desktop">Google</td>
      <td class="data-cell grade partial" sorttable_customkey="59.5">C&nbsp;&nbsp;</td>
      <td class="data-cell grade partial" sorttable_customkey="53.6">C&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/mistral-large-3/" target="_blank" title="data: ">
          <u>Mistral Large 3</u>
        </a>
        <span class="only-mobile">Mistral AI</span>
      </td>
      <td class="only-desktop">Mistral AI</td>
      <td class="data-cell grade partial" sorttable_customkey="54.08">C&nbsp;&nbsp;</td>
      <td class="data-cell grade partial" sorttable_customkey="58.93">C&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/mistral-small-4/" target="_blank" title="data: ">
          <u>Mistral Small 4</u>
        </a>
        <span class="only-mobile">Mistral AI</span>
      </td>
      <td class="only-desktop">Mistral AI</td>
      <td class="data-cell grade partial" sorttable_customkey="54.08">C&nbsp;&nbsp;</td>
      <td class="data-cell grade partial" sorttable_customkey="58.93">C&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/grok-4.5/" target="_blank" title="data: ">
          <u>Grok 4.5</u>
        </a>
        <span class="only-mobile">xAI</span>
      </td>
      <td class="only-desktop">xAI</td>
      <td class="data-cell grade partial" sorttable_customkey="57.33">C&nbsp;&nbsp;</td>
      <td class="data-cell grade partial" sorttable_customkey="51.53">C&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/command-a-plus/" target="_blank" title="data: ">
          <u>C4AI Command A Plus</u>
        </a>
        <span class="only-mobile">Cohere</span>
      </td>
      <td class="only-desktop">Cohere</td>
      <td class="data-cell grade partial" sorttable_customkey="55.66">C&nbsp;&nbsp;</td>
      <td class="data-cell grade partial" sorttable_customkey="51.28">C&nbsp;&nbsp;</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/claude-opus-4-7/" target="_blank" title="data: ">
          <u>Claude Opus 4.7</u>
        </a>
        <span class="only-mobile">Anthropic</span>
      </td>
      <td class="only-desktop">Anthropic</td>
      <td class="data-cell grade partial" sorttable_customkey="56.45">C&nbsp;&nbsp;</td>
      <td class="data-cell grade closed" sorttable_customkey="48.92">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/claude-mythos-preview/" target="_blank" title="data: ">
          <u>Claude Mythos Preview</u>
        </a>
        <span class="only-mobile">Anthropic</span>
      </td>
      <td class="only-desktop">Anthropic</td>
      <td class="data-cell grade partial" sorttable_customkey="56.45">C&nbsp;&nbsp;</td>
      <td class="data-cell grade closed" sorttable_customkey="48.92">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/claude-opus-5/" target="_blank" title="data: ">
          <u>Claude Opus 5</u>
        </a>
        <span class="only-mobile">Anthropic</span>
      </td>
      <td class="only-desktop">Anthropic</td>
      <td class="data-cell grade partial" sorttable_customkey="56.45">C&nbsp;&nbsp;</td>
      <td class="data-cell grade closed" sorttable_customkey="48.92">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/claude-sonnet-5/" target="_blank" title="data: ">
          <u>Claude Sonnet 5</u>
        </a>
        <span class="only-mobile">Anthropic</span>
      </td>
      <td class="only-desktop">Anthropic</td>
      <td class="data-cell grade partial" sorttable_customkey="56.45">C&nbsp;&nbsp;</td>
      <td class="data-cell grade closed" sorttable_customkey="48.92">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/claude-mythos-5-fable-5/" target="_blank" title="data: ">
          <u>Claude Mythos 5 / Claude Fable 5</u>
        </a>
        <span class="only-mobile">Anthropic</span>
      </td>
      <td class="only-desktop">Anthropic</td>
      <td class="data-cell grade partial" sorttable_customkey="56.45">C&nbsp;&nbsp;</td>
      <td class="data-cell grade closed" sorttable_customkey="48.92">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/claude-opus-4-8/" target="_blank" title="data: ">
          <u>Claude Opus 4.8</u>
        </a>
        <span class="only-mobile">Anthropic</span>
      </td>
      <td class="only-desktop">Anthropic</td>
      <td class="data-cell grade partial" sorttable_customkey="56.45">C&nbsp;&nbsp;</td>
      <td class="data-cell grade closed" sorttable_customkey="48.92">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/muse-image/" target="_blank" title="data: ">
          <u>Muse Image</u>
        </a>
        <span class="only-mobile">Meta</span>
      </td>
      <td class="only-desktop">Meta</td>
      <td class="data-cell grade partial" sorttable_customkey="53.17">C&nbsp;&nbsp;</td>
      <td class="data-cell grade closed" sorttable_customkey="49.66">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/muse-spark/" target="_blank" title="data: ">
          <u>Muse Spark</u>
        </a>
        <span class="only-mobile">Meta</span>
      </td>
      <td class="only-desktop">Meta</td>
      <td class="data-cell grade partial" sorttable_customkey="53.61">C&nbsp;&nbsp;</td>
      <td class="data-cell grade closed" sorttable_customkey="48.64">D+</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/phi-4/" target="_blank" title="data: ">
          <u>Phi-4</u>
        </a>
        <span class="only-mobile">Microsoft</span>
      </td>
      <td class="only-desktop">Microsoft</td>
      <td class="data-cell grade closed" sorttable_customkey="33.3">D&nbsp;&nbsp;</td>
      <td class="data-cell grade closed" sorttable_customkey="24.54">F&nbsp;&nbsp;</td>
    </tr>
  </tbody>
</table>

### Summaries currently being evaluated

We are currently evaluating 1 public summaries. Their scores and our
notes will be published shortly. In the meantime, you can access the
public summary through the details page by clicking the model name.

<table id="table-WIP" class="sortable">
  <thead>
    <tr>
      <th>Model</th>
      <th class="only-desktop">Provider</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="name-cell">
        <a href="evals/pllum/" target="_blank" title="data: ">
          <u>PLLuM 2512 Base</u>
        </a>
        <span class="only-mobile">Ministry of Digital Affairs of Poland</span>
      </td>
      <td class="only-desktop">Ministry of Digital Affairs of Poland</td>
    </tr>
  </tbody>
</table>

### Models with missing summaries

Based on our preliminary analysis, we have assessed the following models
as requiring a mandatory public summary, but which we could not
discover.

<table id="table-missing" class="sortable">
  <thead>
    <tr>
      <th>Model</th>
      <th class="only-desktop">Provider</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td class="name-cell">
        <a href="evals/claude-sonnet-4-6/" target="_blank" title="data: ">
          <u>Claude Sonnet 4.6</u>
        </a>
        <span class="only-mobile">Anthropic</span>
      </td>
      <td class="only-desktop">Anthropic</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/flux-2-max/" target="_blank" title="data: ">
          <u>FLUX.2 [max]</u>
        </a>
        <span class="only-mobile">Black Forest Labs</span>
      </td>
      <td class="only-desktop">Black Forest Labs</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/apriel-1-5/" target="_blank" title="data: ">
          <u>Apriel 1.5 15B Thinker</u>
        </a>
        <span class="only-mobile">ServiceNow</span>
      </td>
      <td class="only-desktop">ServiceNow</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/claude-opus-4-6/" target="_blank" title="data: ">
          <u>Claude Opus 4.6</u>
        </a>
        <span class="only-mobile">Anthropic</span>
      </td>
      <td class="only-desktop">Anthropic</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/gpt-5-6-sol/" target="_blank" title="data: ">
          <u>GPT-5.6 Sol</u>
        </a>
        <span class="only-mobile">OpenAI</span>
      </td>
      <td class="only-desktop">OpenAI</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/flux-2-klein/" target="_blank" title="data: ">
          <u>FLUX.2 Klein</u>
        </a>
        <span class="only-mobile">Black Forest Labs</span>
      </td>
      <td class="only-desktop">Black Forest Labs</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/gpt-oss/" target="_blank" title="data: ">
          <u>GPT-OSS</u>
        </a>
        <span class="only-mobile">OpenAI</span>
      </td>
      <td class="only-desktop">OpenAI</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/granite-4-1/" target="_blank" title="data: ">
          <u>Granite 4.1</u>
        </a>
        <span class="only-mobile">IBM</span>
      </td>
      <td class="only-desktop">IBM</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/flux-2/" target="_blank" title="data: ">
          <u>FLUX.2</u>
        </a>
        <span class="only-mobile">Black Forest Labs</span>
      </td>
      <td class="only-desktop">Black Forest Labs</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/gpt-5-6-terra/" target="_blank" title="data: ">
          <u>GPT-5.6 Terra</u>
        </a>
        <span class="only-mobile">OpenAI</span>
      </td>
      <td class="only-desktop">OpenAI</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/claude-opus-4-1/" target="_blank" title="data: ">
          <u>Claude Opus 4.1</u>
        </a>
        <span class="only-mobile">Anthropic</span>
      </td>
      <td class="only-desktop">Anthropic</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/gpt-image-2/" target="_blank" title="data: ">
          <u>GPT Image 2</u>
        </a>
        <span class="only-mobile">OpenAI</span>
      </td>
      <td class="only-desktop">OpenAI</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/sora-2/" target="_blank" title="data: ">
          <u>Sora 2</u>
        </a>
        <span class="only-mobile">OpenAI</span>
      </td>
      <td class="only-desktop">OpenAI</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/granite-4-0-h/" target="_blank" title="data: ">
          <u>Granite 4.0 H</u>
        </a>
        <span class="only-mobile">IBM</span>
      </td>
      <td class="only-desktop">IBM</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/palmyra-x5/" target="_blank" title="data: ">
          <u>Palmyra X5</u>
        </a>
        <span class="only-mobile">WRITER</span>
      </td>
      <td class="only-desktop">WRITER</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/claude-haiku-4-5/" target="_blank" title="data: ">
          <u>Claude Haiku 4.5</u>
        </a>
        <span class="only-mobile">Anthropic</span>
      </td>
      <td class="only-desktop">Anthropic</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/claude-opus-4-5/" target="_blank" title="data: ">
          <u>Claude Opus 4.5</u>
        </a>
        <span class="only-mobile">Anthropic</span>
      </td>
      <td class="only-desktop">Anthropic</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/north-mini-code/" target="_blank" title="data: ">
          <u>North Mini Code 1.0</u>
        </a>
        <span class="only-mobile">Cohere</span>
      </td>
      <td class="only-desktop">Cohere</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/claude-sonnet-4-5/" target="_blank" title="data: ">
          <u>Claude Sonnet 4.5</u>
        </a>
        <span class="only-mobile">Anthropic</span>
      </td>
      <td class="only-desktop">Anthropic</td>
    </tr>
    <tr>
      <td class="name-cell">
        <a href="evals/veo-3-1/" target="_blank" title="data: ">
          <u>Veo 3.1</u>
        </a>
        <span class="only-mobile">Google</span>
      </td>
      <td class="only-desktop">Google</td>
    </tr>
  </tbody>
</table>

## Why we started this project

- We contend that compliance cannot be *fait accompli*, and that the
  public summaries are a key factor in creating transparency and
  enabling rights enforcement. Towards this, our work also acts as a
  guide for providers who are yet to publish their summaries to consider
  how to do so with the highest possible quality and utility.
- Compliance also invites practices that are intentionally or
  unintentionally deficient in achieving the goals. Our work serves as a
  useful tool for describing how and where and why certain practices are
  \'bad\', e.g., where they use obfuscation, do not provide stated
  information. Using this, we can detect trends or patterns in whether
  the same issues occur in many summaries, and if so, how they can be
  collectively addressed through guidance, or enforced with priority.
- The largest challenge in undertaking this work has been finding public
  summaries as there is no consistent format or practice for how they
  should be provided. For this, we provide
  [recommendations](recommendations).
- The template for public summaries provided by the AI Office is
  intended to be revised with time to improve the state of documentation
  as well as to better guide the providers. We also provide
  [recommendations](recommendations) for these to improve the quality
  and accessibility of the public summaries.
