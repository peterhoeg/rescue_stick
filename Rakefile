IMAGES = [
  'http://www.ibiblio.org/pub/micro/pc-stuff/freedos/files/distributions/1.0/fdbasecd.iso',
  'http://northwind.sg/files/fdos-2011-05-11.img.gz',
]

desc "Create grub.cfg"
task :grub do
end

desc "Download images"
task :download do
  IMAGES.each { |i| system "cd images ; wget -c '#{i}' ; cd .." }
end

task :default => [ :grub ]
