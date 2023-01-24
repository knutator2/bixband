rvm ruby-3.0.0 do rvm gemset create 2.7
sudo bundle install
gem install eventmachine -- --with-cppflags=-I/usr/local/opt/openssl/include 
bundle install
