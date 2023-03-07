
example: example.cxx ../GPUTreeShap/gpu_treeshap.h ../warp-primitives/include/amd_warp_primitives.h
	hipcc -Wall -std=c++14 -I../GPUTreeShap -I../warp-primitives/include -o example example.cxx

clean:
	rm -f example
