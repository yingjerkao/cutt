target_sources_local(cutt
    PRIVATE
        CudaMemcpy.cu
        #CudaUtils.cu
        cuttGpuModelKernel.cu 
        cuttKernel.cu        
        cutt.cpp
        cuttGpuModel.cpp
        cuttplan.cpp
        cuttTimer.cpp

        CudaMemcpy.h
        #CudaUtils.h    
        cuttGpuModelKernel.h
        cuttKernel.h
        cuttGpuModel.h
        cuttplan.h
        cuttTimer.h
        LRUCache.h
        inv_vector.h
        cuttTypes.h
        calls.h
        
)
