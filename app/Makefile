.PHONY: bench
bench:
	@ssh isu-myself '~/private_isu.git/benchmarker/bin/benchmarker -u ~/private_isu.git/benchmarker/userdata -t http://192.168.1.10/'

.PHONY: change-go-version
change-go-version:
	@ssh isu-myself2 'sudo systemctl disable --now isu-ruby'
	@ssh isu-myself2 'sudo systemctl enable --now isu-go'

.PHONY: foobar
foobar:
	@echo "foobar"

