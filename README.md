# Awesome Cancer AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Artificial intelligence applied to cancer prevention, detection, diagnosis and treatment.

Entries are open source code, open model weights or open data that have been used in cancer research. Where a project has gated weights, a non-commercial license or a dependency on a proprietary API, the description says so.

> **Disclaimer:** This list is for research and educational purposes. Nothing here is medical advice. Consult a qualified clinician for diagnosis or treatment decisions.

## Contents

- [Risk Prediction and Early Detection](#risk-prediction-and-early-detection)
- [Pathology](#pathology)
- [Radiology](#radiology)
- [Genomics and Molecular Profiling](#genomics-and-molecular-profiling)
- [Prognosis and Treatment Response](#prognosis-and-treatment-response)
- [Clinical Trial Matching](#clinical-trial-matching)
- [Clinical Language Models and Agents](#clinical-language-models-and-agents)
- [Drug Discovery and Target Identification](#drug-discovery-and-target-identification)
- [Pediatric and Rare Cancers](#pediatric-and-rare-cancers)
- [Datasets and Benchmarks](#datasets-and-benchmarks)
- [Surveys](#surveys)

## Risk Prediction and Early Detection

- [Sybil](https://github.com/reginabarzilaygroup/Sybil) - Predicts one to six year lung cancer risk from a single low-dose CT scan.
- [Mirai](https://github.com/yala/Mirai) - Five-year breast cancer risk prediction from screening mammograms, with MIT-licensed model weights.

## Pathology

- [Prov-GigaPath](https://github.com/prov-gigapath/prov-gigapath) - Whole-slide pathology foundation model trained on 1.3 billion tiles, released with Apache-2.0 weights.
- [UNI](https://github.com/mahmoodlab/UNI) - Self-supervised pan-cancer tile encoder for H&E histopathology; weights are gated and non-commercial.
- [CONCH](https://github.com/mahmoodlab/CONCH) - Vision-language pathology model for zero-shot classification, retrieval and captioning; gated, non-commercial weights.
- [TITAN](https://github.com/mahmoodlab/TITAN) - Whole-slide-level multimodal foundation model producing slide embeddings and reports; gated, non-commercial weights.
- [Virchow2](https://huggingface.co/paige-ai/Virchow2) - Pan-cancer tile encoder trained on 3.1 million slides; weights only, gated and non-commercial.
- [H-optimus-0](https://huggingface.co/bioptimus/H-optimus-0) - 1.1 billion parameter histology feature extractor released under Apache-2.0 with gated download.
- [CLAM](https://github.com/mahmoodlab/CLAM) - Weakly supervised attention-based multiple-instance learning for whole-slide classification.
- [TRIDENT](https://github.com/mahmoodlab/TRIDENT) - Toolkit for slide segmentation, patching and feature extraction with 20+ pathology foundation models; non-commercial license.
- [STAMP](https://github.com/KatherLab/STAMP) - End-to-end weakly supervised pipeline from whole-slide images to biomarker and survival prediction.
- [HistoQC](https://github.com/choosehappy/HistoQC) - Quality control and artifact detection for digital pathology slides.

## Radiology

- [nnU-Net](https://github.com/MIC-DKFZ/nnUNet) - Self-configuring segmentation framework and the standard baseline for tumor segmentation challenges.
- [MONAI](https://github.com/Project-MONAI/MONAI) - PyTorch framework for medical imaging deep learning, widely used for tumor segmentation and classification.
- [MONAI Label](https://github.com/Project-MONAI/MONAILabel) - AI-assisted interactive annotation server with 3D Slicer and OHIF plugins.
- [TotalSegmentator](https://github.com/wasserth/TotalSegmentator) - Segments over 100 anatomical structures in CT and MR for organ-at-risk and tumor-burden context; some task weights are non-commercial.
- [MedSAM](https://github.com/bowang-lab/MedSAM) - Segment Anything fine-tuned for promptable 2D medical image segmentation including tumors and lesions.
- [MedSAM2](https://github.com/bowang-lab/MedSAM2) - SAM2-based 3D and video medical segmentation with lesion tracking workflows.
- [SAM-Med3D](https://github.com/uni-medical/SAM-Med3D) - Promptable 3D volumetric segmentation model with released weights.
- [SegVol](https://github.com/BAAI-DCAI/SegVol) - Universal interactive CT segmentation driven by text and spatial prompts.
- [Merlin](https://github.com/StanfordMIMI/Merlin) - 3D abdominal CT vision-language foundation model trained on reports and EHR data, with ungated MIT weights.
- [CT-FM](https://github.com/project-lighter/CT-FM) - Self-supervised 3D CT foundation model pretrained on 148,000 scans.
- [VISTA-3D](https://github.com/Project-MONAI/VISTA) - NVIDIA 3D CT segmentation foundation model covering 127 classes with prompt support.
- [RadFM](https://github.com/chaoyi-wu/RadFM) - Generalist radiology vision-language model for 2D and 3D scans; weight license is unclear.
- [BraTS Toolkit](https://github.com/neuronflow/BraTS-Toolkit) - Preprocessing, segmentation and fusion pipeline for glioma MRI built on BraTS algorithms.
- [TorchIO](https://github.com/fepegar/torchio) - Medical image loading, preprocessing, augmentation and patch sampling for PyTorch.
- [PyRadiomics](https://github.com/AIM-Harvard/pyradiomics) - Standardized radiomics feature extraction used in tumor phenotyping pipelines.

## Genomics and Molecular Profiling

- [DeepSomatic](https://github.com/google/deepsomatic) - Deep learning somatic variant caller for tumor-normal and tumor-only sequencing across Illumina, PacBio and ONT.
- [DeepVariant](https://github.com/google/deepvariant) - Deep learning germline variant caller that DeepSomatic is built on.
- [GATK Mutect2](https://github.com/broadinstitute/gatk) - Probabilistic somatic variant caller that serves as the classical baseline for deep learning callers.
- [cBioPortal](https://github.com/cBioPortal/cbioportal) - Web platform for exploring and analyzing cancer genomics cohorts.
- [cBioPortal Datahub](https://github.com/cBioPortal/datahub) - Curated, load-ready public cancer genomics studies including TCGA and MSK-IMPACT.
- [pVACtools](https://github.com/griffithlab/pVACtools) - Neoantigen prediction and prioritization suite for personalized cancer vaccines.
- [OncoKB Annotator](https://github.com/oncokb/oncokb-annotator) - Annotates variant files with clinical levels of evidence; requires an API token and a commercial license for non-academic use.
- [CIViC](https://civicdb.org) - Community-curated, CC0 knowledgebase for clinical interpretation of cancer variants.
- [SigProfilerExtractor](https://github.com/AlexandrovLab/SigProfilerExtractor) - De novo extraction of mutational signatures from cancer genomes.
- [Borzoi](https://github.com/calico/borzoi) - Predicts RNA-seq coverage from DNA sequence for regulatory variant interpretation.
- [scGPT](https://github.com/bowang-lab/scGPT) - Single-cell foundation model pretrained on 33 million cells.
- [Geneformer](https://huggingface.co/ctheodoris/Geneformer) - Transformer pretrained on human single-cell transcriptomes for in silico perturbation.
- [DepMap](https://depmap.org/portal) - Cancer Dependency Map of CRISPR screens and omics across cancer cell lines, released under CC BY 4.0.

## Prognosis and Treatment Response

- [scikit-survival](https://github.com/sebp/scikit-survival) - Survival analysis with a scikit-learn compatible API.
- [pycox](https://github.com/havakv/pycox) - PyTorch implementations of DeepSurv, DeepHit and other neural survival models.
- [CancerFoundation](https://github.com/BoevaLab/CancerFoundation) - Single-cell foundation model trained only on malignant cells for drug response prediction; preprint stage.
- [HoneyBee](https://github.com/lab-rasool/HoneyBee) - Multimodal oncology embedding framework for clinical text, imaging and molecular data; non-commercial license.

## Clinical Trial Matching

- [TrialMatchAI](https://github.com/cbib/TrialMatchAI) - Locally deployable patient-to-trial matching built on open LLMs and validated on oncology patients.
- [TrialGPT](https://github.com/ncbi-nlp/TrialGPT) - Zero-shot trial retrieval, criterion matching and ranking from the NIH; requires an OpenAI API key.
- [MatchMiner-AI](https://github.com/dfci/matchminer-ai-inference) - Cancer trial search and ranking trained on synthetic EHR data with open weights; non-commercial license.
- [MatchMiner](https://github.com/dfci/matchminer) - Rule-based genomic and clinical precision oncology trial matching platform from Dana-Farber.

## Clinical Language Models and Agents

- [DeepPhe](https://github.com/DeepPhe/DeepPhe-Release) - Cancer phenotype extraction from pathology and clinical notes built on cTAKES.
- [LLM_RAG_Agent](https://github.com/Dyke-F/LLM_RAG_Agent) - Autonomous multimodal precision oncology agent combining GPT-4 with imaging, pathology and OncoKB tools.
- [MTBBench](https://github.com/bunnelab/MTBBench) - Multimodal longitudinal benchmark for molecular tumor board decision making, including agentic tasks.
- [Healthcare Agent Orchestrator](https://github.com/Azure-Samples/healthcare-agent-orchestrator) - Multi-agent tumor board accelerator from Microsoft; requires Azure OpenAI.
- [ToolUniverse](https://github.com/mims-harvard/ToolUniverse) - Over 1,000 scientific tools for AI agents, including a precision oncology skill.
- [TxAgent](https://github.com/mims-harvard/TxAgent) - Therapeutic reasoning agent with 211 tools and open Llama-based weights.
- [Biomni](https://github.com/snap-stanford/Biomni) - General biomedical research agent with optional open weights.

## Drug Discovery and Target Identification

- [Boltz](https://github.com/jwohlwend/boltz) - MIT-licensed biomolecular structure and binding affinity prediction at AlphaFold 3 level.
- [Chai-1](https://github.com/chaidiscovery/chai-lab) - Apache-2.0 multimodal structure prediction for proteins, ligands and antibodies; later versions are closed.
- [OpenFold3](https://github.com/aqlaboratory/openfold-3) - Fully open AlphaFold 3-style co-folding model in preview.
- [AlphaFold 3](https://github.com/google-deepmind/alphafold3) - Reference structure prediction pipeline; weights require a request and are non-commercial.
- [DiffDock](https://github.com/gcorso/DiffDock) - Diffusion-based blind molecular docking.
- [TxGNN](https://github.com/mims-harvard/TxGNN) - Zero-shot drug repurposing graph model covering 17,000 diseases including cancers.
- [Therapeutics Data Commons](https://github.com/mims-harvard/TDC) - Benchmarks for therapeutic machine learning including GDSC drug response and DrugComb synergy tasks.
- [REINVENT 4](https://github.com/MolecularAI/REINVENT4) - Reinforcement learning generative chemistry for de novo molecular design.
- [Chronos](https://github.com/broadinstitute/chronos) - Gene-effect inference for CRISPR knockout screens underlying DepMap dependency scores.
- [ESM](https://github.com/evolutionaryscale/esm) - Protein language models; ESM C is open while ESM3 weights are non-commercial.
- [DeepPurpose](https://github.com/kexinhuang12345/DeepPurpose) - Drug-target interaction and repurposing toolkit.

## Pediatric and Rare Cancers

- [Kids First Data Resource Center](https://kidsfirstdrc.org) - NIH genomic and clinical data on pediatric cancer and congenital disorders; open summary data with controlled access through dbGaP.
- [Pediatric Cancer Data Commons](https://commons.cri.uchicago.edu/pcdc) - Harmonized clinical data from 16 disease consortia spanning leukemia, CNS, germ cell, liver and bone tumors; free exploration, line-level data by application.
- [St. Jude Cloud](https://www.stjude.cloud) - Pediatric cancer genomics platform with the PeCan variant knowledgebase and ProteinPaint visualization.
- [Childhood Cancer Data Initiative Hub](https://ccdi.cancer.gov/home) - NCI entry point to childhood cancer data and the Molecular Targets Platform.
- [OpenPedCan](https://github.com/PediatricOpenTargets/OpenPedCan-analysis) - Open analysis pipeline harmonizing pediatric cancer data from OpenPBTA, TARGET and Kids First; CC0 data and BSD-3 code.
- [Children's Brain Tumor Network](https://cbtn.org) - Consortium of 35 institutions sharing pediatric brain tumor biosamples, imaging and clinical data with collaborating investigators.

## Datasets and Benchmarks

- [NCI Genomic Data Commons](https://portal.gdc.cancer.gov) - Harmonized cancer genomics repository hosting TCGA, TARGET and CPTAC with open and controlled tiers.
- [The Cancer Imaging Archive](https://www.cancerimagingarchive.net) - De-identified DICOM cancer imaging collections, many under CC BY.
- [LIDC-IDRI](https://www.cancerimagingarchive.net/collection/lidc-idri) - Thoracic CT with lung nodule annotations from four radiologists.
- [CAMELYON17](https://camelyon17.grand-challenge.org) - Lymph node metastasis detection in breast cancer whole-slide images.
- [PANDA](https://www.kaggle.com/competitions/prostate-cancer-grade-assessment) - Gleason grading of 10,616 prostate biopsy slides.
- [BraTS](https://www.synapse.org/brats) - Annual multi-task brain tumor MRI segmentation benchmark.
- [CPTAC](https://pdc.cancer.gov) - Matched proteomic and genomic data across 12 cancer types from the NCI proteogenomics consortium.
- [ICGC ARGO](https://platform.icgc-argo.org) - Uniformly analyzed whole-genome and clinical data, successor to PCAWG.
- [AACR Project GENIE](https://genie.cbioportal.org) - Real-world clinico-genomic registry of 289,000 samples from 20 institutions.

## Surveys

- [Pathology Foundation Models](https://arxiv.org/abs/2407.21317) - Review of pathology foundation models for diagnosis, survival and biomarker prediction.
- [pathology-foundation-models](https://github.com/georg-wolflein/pathology-foundation-models) - Comparison table of patch-level and slide-level pathology foundation models.
- [MedLLMsPracticalGuide](https://github.com/AI-in-Health/MedLLMsPracticalGuide) - Survey and resource list for medical large language models.

## Related Lists

- [awesome-healthcare](https://github.com/kakoni/awesome-healthcare#readme) - Open source healthcare software.
- [Awesome-Bioinformatics](https://github.com/danielecook/Awesome-Bioinformatics#readme) - Bioinformatics libraries and software.
- [awesome-pathology](https://github.com/open-pathology/awesome-pathology#readme) - Digital and computational pathology resources.
- [awesome-medical-imaging](https://github.com/fepegar/awesome-medical-imaging#readme) - Medical imaging software.
- [awesome-cancer-variant-resources](https://github.com/seandavi/awesome-cancer-variant-resources#readme) - Cancer variant knowledgebases and databases.

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first. Projects that are no longer maintained are kept in the [archive](archive.md).
