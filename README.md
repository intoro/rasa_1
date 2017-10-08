install python pip virtualenv
pip install rasa_nlu



            If you want to use the bleeding edge version use github + setup.py:

            git clone https://github.com/RasaHQ/rasa_nlu.git
            cd rasa_nlu
            pip install -r requirements.txt
            python setup.py install



installing spacy just requires (for more information visit the spacy docu):

pip install -U spacy
python -m spacy download en


------------------------------------------------------------------
                                      Anaconda

                                      cd /tmp
                                      curl -O https://repo.continuum.io/archive/Anaconda3-4.2.0-Linux-x86_64.sh
                                          We can now verify the data integrity of the installer with cryptographic hash verification
                                          through the SHA-256 checksum. We’ll use the sha256sum command along with the filename of the script:

                                      sha256sum Anaconda3-4.2.0-Linux-x86_64.sh

                                      bash Anaconda3-4.2.0-Linux-x86_64.sh

                                      source ~/.bashrc

                                        play around if using virtualenv


                                      conda install scikit-learn

------------------------------------------------------------------

pip install -U sklearn-crfsuite
  Using pip:

pip install -U scikit-learn scipy sklearn-crfsuite

pip install scikit-learn==0.18.1 scipy==0.19.0 matplotlib==1.5.3


pip install git+https://github.com/mit-nlp/MITIE.git





.
