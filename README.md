# Simulating Robot Worlds Workshop Website

## Local Development (Ubuntu)

1. **Install Ruby and Bundler**

```bash
sudo apt update
sudo apt install ruby-full build-essential zlib1g-dev
sudo gem install bundler
```

2. **Install Jekyll and dependencies**

```bash
bundle install
```

3. **Run the local server**

```bash
jekyll serve
```

4. **View the site**

Open your browser to: [http://localhost:4000](http://localhost:4000)

---

If you encounter dependency issues, try removing `Gemfile.lock` and running `bundle install` again. 


This repository was initialized from CORR workshop page that  itself was initialized from https://github.com/objects-structure-causality/objects-structure-causality.github.io, which itself is based on https://github.com/orlrworkshop/orlrworkshop.github.io and https://github.com/oolworkshop/oolworkshop.github.io and https://github.com/baicsworkshop/baicsworkshop.github.io/ 