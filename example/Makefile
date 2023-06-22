
example: example.cxx ../GPUTreeShap/gpu_treeshap.h ../GPUTreeShap/amd_warp_primitives.h
	hipcc -Wall -std=c++14 -I../GPUTreeShap -I../GPUTreeShap/include -o example example.cxx

clean:
	rm -f example
