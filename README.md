## Hacking LLMs for Feminism

Can you deconstruct oppressive notions in today's LLMs and use hacker/adversarial thinking to build a more feminist AI?

This repository explores the question and introduces ideas for hacking LLMs for feminism. So far it:

- Explores simple and advanced prompt engineering
- Takes inspiration from successful adversarial attacks
- Identifies conceptual links in text embeddings
- More ideas (add yours here!)

Each notebook guides participants of a [Feminist AI LAN Party](https://feministai.party) through exercises, questions and conversations. It's more fun to hack with friends, so it's encouraged to do just that by [hosting your own party]().

### Setup and Requirements

Most of these notebooks can be run locally on your own computer with [Mozilla's Llamafiles](https://github.com/Mozilla-Ocho/llamafile).

Some notebooks work better if you have an LLM set up for inference via the Local Area Network (LAN). Stay tuned for a full instruction setup with photos on how to do this on your own GPUs or with donated or shared computers.

To get your local computer setup:

1. Install at least one, but preferably several [llamafiles](https://github.com/Mozilla-Ocho/llamafile). Follow the Readme instructions there and test that it is working properly by running the file and testing the chat browser that pops up.
2. Clone this repository onto your computer.
3. Open a new terminal and set up a [miniconda](https://www.anaconda.com/docs/getting-started/miniconda/install) or [virtualenv](https://virtualenv.pypa.io/en/latest/installation.html) with at least Python3.10. Activate this environment. You will now see (environment_name) in your terminal.
4. In that same terminal, navigate to the root folder of this repository on your computer (usually `cd FULL_PATH_TO_THIS_FOLDER` ) and install the requirements.txt file using `pip install -r requirements.txt`.
5. In that same terminal window, run `jupyter notebook`.

You should now see a browser window that opens up and the notebooks will be viewable. Click on one to get started!

In case there are folks who are new to Python/Jupyter in the room, take time to help one another getting set up. Contributions to improve these instructions very welcome!

### Contributions

Contributions are greatly welcome from any and all feminist hackers interested in exposing and challenging oppressive systems in LLMs.

*Feminist AI LAN Party Hosts and Attendees*: Find bugs? Have a suggestion? Develop a new idea or attack? Please share!

*Researchers*: If you already have a research library or article that people can or should take inspiration from, please share any open-source-able work! If your code is not yet open-sourced or shareable, please feel free to also open an Issue describing an idea or sharing your research.

*Hackers/Programmers*: If you are good at Python or attacking systems but new to LLMs, feel free to peruse open ideas and see if you can implement an already shared idea. Collaboration is key to destroying oppression! :)

*Data Scientists/ML Engineers*: Have research or ideas you want to implement? Host a party or pair up with someone to add notebooks to the conversation!

*Everyone*: Feminism is for everybody. If you find anything you'd like to add or improve, please feel free to open an Issue, send a pull request or even just say hi.

There are a few open issues already, so go take a look in case you can help!

In general, please follow the following workflow:

1. Fork this repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes. Please make sure that any new libraries get added to the requirements and try to test backwards compatibility with other requirements or make a note of any conflicts in your pull request.
4. Push your branch: git push origin feature-name.
5. Create a pull request.

Thank you for any and all improvements and contributions!

### License

This repository uses a [GNU General Public License](LICENSE).

If you need a different license in order to contribute, please open an issue to discuss.
