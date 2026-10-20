# Bridge2AI Face-to-Face Materials

This site is hosted [here](https://dmice.ohsu.edu/bedricks/b2ai_f2f_oct_2026/)

- [Dataset Documentation](https://docs.b2ai-voice.org/)
  - Description of protocol, data use restrictions, study metadata, etc.
- The Datasets!
  - See these [logistical notes](accessing_data.qmd)
  - [Bridge2AI-Voice Adult dataset download](https://physionet.org/content/b2ai-voice/)
    - Shorter and more focused overview, including brief code example.
    - Download the full dataset, get the DOI for citing, etc.
    - [Dataset dashboard](https://b2ai-voice.org/bridge2ai-voice-dataset/adult-dashboard/)
  - [Bridge2AI-Voice Pediatric dataset download](https://physionet.org/content/b2ai-voice-pediatric)
    - [Dataset dashboard](https://b2ai-voice.org/bridge2ai-voice-dataset/pediatric-dashboard/)
- [RedCap Data Dictionary](https://github.com/eipm/bridge2ai-redcap)
  - Exhaustive description of all fields, examples of questionnaires, links to acoustic stimuli, map of protocols to questionnaires/acoustic tasks, etc., for both the adult and pediatric protocols.
  - The data dictionary in [CSV](https://github.com/eipm/bridge2ai-redcap/blob/main/data/bridge2ai_voice_project_data_dictionary.csv) format (an XML version also exists on Github, if that's more your jam)
- [FHIR Schema](https://kind-lab.github.io/vbai-fhir/toc.html)
  - Machine-readable metadata schema, for those of us who are into that sort of thing. 🤓
- [b2aiprep](https://github.com/sensein/b2aiprep) library: The Python library that performs the data processing of the raw audio to produce the dataset (feature extraction, etc.)
- [FAQ About LLM Usage](https://usf.app.box.com/s/6w7iclfnryj81u2lo4wc3brs6cjj8d7g)
