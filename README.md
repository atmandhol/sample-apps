# Sample Apps

This repo has 3 kinds of sources for 2 apps.

### Apps
* where-for-dinner
* spring-petclinic

### Source Types
* source - raw source code that can be built
* source-image - source is packaged as an imgpkg bundle. This is useful to simulate innerloop development workflows and can be pulled using OCIRepository or ImageRepository CRs.
* prebuilt - App built using kpack and ready to deploy.
* helm - Sample helm chart

```bash
root
├─ source/
│  ├─ wfd/
│  └─ spring-petclinic/
├─ prebuilt/
│  ├─ wfd/
│  └─ spring-petclinic/
├─ source-image/
│  ├─ wfd/
│  └─ spring-petclinic/
```
