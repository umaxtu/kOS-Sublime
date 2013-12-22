require 'json'
require 'plist'

OUTFILE = 'kos.tmLanguage'
INFILE = OUTFILE + '.json'

task :default => :build

task :build do
  json = JSON.parse(File.read(INFILE))
  File.open(OUTFILE, 'w') { |f| f.write json.to_plist }
end