# Instructions
# 1) gem install guard guard-shell growl_notify
# 2) run 'guard'
# 3) Change tests and watch as Guard automatically runs rake

guard 'shell' do
	watch(%r{^koans/.+\.rb$}) {puts `rake`}
end