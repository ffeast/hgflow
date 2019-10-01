# hgflow version that just works
This is the version of [hgflow](https://bitbucket.org/yujiewu/hgflow/wiki/Home) that works with modern mercurial versions.
It's been a pain to find the right version so I've just mirrored it here.
## Installation
Super concise installation guide (refer to the original [docs](https://bitbucket.org/yujiewu/hgflow/wiki/Home) for details):
 1. `mkdir ~/.hgext && curl https://raw.githubusercontent.com/ffeast/hgflow/master/hgflow.py > ~/.hgext/hgflow.py`
 2. add the following line into your `~/.hgrc`  under the `[extensions]`  section
**hgflow = ~/.hgext/hgflow.py**
