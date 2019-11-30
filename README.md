# CS6476-TermProject

## Project Website
  https://akrishna77.github.io/visual-relationships/

## Running the Notebook
  Create a virtual environment, to avoid dependency mismatches.
  ```
  conda create -n cvproj python=3.7.4
  conda activate cvproj
  ```

  Install dependencies from `requirements.txt`.
  ```
  pip install -r requirements.txt
  ```

## Implemented so far
  Faster-RCNN - [Satya Mallick's Blog](https://www.learnopencv.com/faster-r-cnn-object-detection-with-pytorch/)
  
  Spacy for S-P-O extraction - [Peter's Github](https://github.com/peter3125/enhanced-subject-verb-object-extraction) - Sticking with this!
  
  [NLTK approach](https://github.com/acrosson/nlp/blob/master/subject_extraction/subject_extraction.py) - Poor performance!

  [Stanford Parser approach](https://playwithml.wordpress.com/2016/06/15/extracting-relations-or-subject-predicate-object-triples/) - Poor Performance!

  Triplet Mining from Dataset
    
  Few-shot learning based approach for Visual Relationship detection -  triplet loss function. (Ongoing)

## Things to explore
    
  Object pair filtering.
  
## Misc

  If you're having trouble viewing the notebook, copy the link to the `.ipynb` file into [Jupyter Notebook Viewer](https://nbviewer.jupyter.org/)!
