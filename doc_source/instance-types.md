# AppStream 2\.0 Instance Families<a name="instance-types"></a>

Amazon AppStream 2\.0 users stream applications from stacks created by an administrator\. Each stack is associated with a fleet\. When you create a fleet, the instance type that you specify determines the hardware of the host computers used for your fleet\. Each instance type offers different compute, memory, and GPU capabilities\. Instance types are grouped into *instance families* based on these capabilities\.

When you create a fleet or image builder, you must select an image that is compatible with the instance family on which you intend to run your fleet\.

+ When launching a new image builder, you are presented with a list of the images in your image registry\. Select the appropriate base image\.

+ When launching a fleet, ensure that the private image you select was created from the appropriate base image\.

The following table summarizes the available instance families and provides the base image naming format for each\. Select an instance type from an instance family based on the requirements of the applications that you plan to stream on your fleet, and match the base image according to the following table\.


| Instance Family | Description | Base Image Name | 
| --- | --- | --- | 
| General Purpose | Basic computing resources for running web browsers and most business applications\. | Base\-Image\-Builder\-MM\-DD\-YYYY | 
| Memory Optimized | Optimized for memory\-intensive applications that process large amounts of data\. | Base\-Image\-Builder\-MM\-DD\-YYYY | 
| Compute Optimized | Optimized for compute\-bound applications that benefit from high performance processors\. | Base\-Image\-Builder\-MM\-DD\-YYYY | 
| Graphics Design | Uses AMD FirePro S7150x2 Server GPUs and AMD Multiuser GPU technology to support graphics applications that use DirectX, OpenGL, or OpenCL\. | Graphics\-Design\-Image\-Builder\-MM\-DD\-YYYY | 
| Graphics Desktop | Uses NVIDIA GRID K520 GPU to support applications that beneﬁt from or require graphics acceleration\. This instance family supports DirectX, OpenGL, OpenCL, and CUDA\. | Graphics\-Desktop\-Image\-Builder\-MM\-DD\-YYYY | 
| Graphics Pro | Uses NVIDIA Tesla M60 GPUs and provide a high\-performance, workstation\-like experience for graphics applications that use DirectX, OpenGL, OpenCL, or CUDA\. | Graphics\-Pro\-Image\-Builder\-MM\-DD\-YYYY | 

For more information, see the following:

+ [Amazon AppStream 2\.0 Windows Image Version History](base-image-version-history.md)

+ [Amazon AppStream 2\.0 Service Limits](limits.md)

+ [AppStream 2\.0 Pricing](https://aws.amazon.com/appstream2/pricing/)