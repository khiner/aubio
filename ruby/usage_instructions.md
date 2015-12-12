  git clone https://github.com/khiner/aubio.git
  cd aubio
  git checkout develop
  make getwaf
  ./waf configure
  ./waf build
  sudo ./waf install
  cd ruby
  gem install bundle
  bundle install
  ./create_samlpe_info_map <path> <pitch_precision>
