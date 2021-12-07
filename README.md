# Sentence Similarity

To be completed...

<!-- ABOUT THE PROJECT -->
## About The Project

To be completed...

### Built Using

* Python 2
* Tensorflow 1.8



<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple steps.

### Requierments

First install the requierments as followed.
  ```sh
  pip install -r requirments.txt
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/MinaHajirezaei/Sentence_Similarity.git
   ```
2. Setup the config file same as per_conf.config
3. Run the training code
   ```sh
   python2 src/SentenceMatchTrainer.py --config_path per_conf.config
   ```

4. Run the training code
   ```sh
   python2 SentenceMatchDecoder.py --model_prefix src/logs/SentenceMatch.quora --in_path persian_test.tsv --out_path result.json --word_vec_path wiki.fa.vec

   ```

<!-- USAGE EXAMPLES -->
## Usage

To be completed...


<!-- ROADMAP -->
## Roadmap
- [x] add support for persian language

See the [open issues](https://github.com/MinaHajirezaei/Sentence_Similarity/issues) for a list of proposed features (and known issues).



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

To be completed...


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

To be completed...
