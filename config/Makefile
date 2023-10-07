build:
	cmake -S . -B ../build/out

run:
	cmake -S . -B ../build/out
	cd ../build/out; sudo make install
	PortifolioWebsiteGenerator

debug:
	cmake -S . -B ../build/out
	cd ../build/out; sudo make install; gdb ./PortifolioWebsiteGenerator core
	r
	