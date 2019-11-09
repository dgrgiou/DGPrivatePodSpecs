# DGPrivatePodSpecs
Private repo for podspec 

See how ref:https://www.raywenderlich.com/5823-how-to-create-a-cocoapod-in-swift

After completing the framework work you have to:

1. Create a Project.podspec file 

``` pod spec create Project  // This creates a spec ```

``` open -a Xcode RWPickFlavor.podspec // Open the spec file ```

2. Import the info and dependencied in .podspec file

3. Add remote podspec repo to this project / Or create a new one
``` pod repo add PrivateRepoName [Your private podspec repo Git URL] ```

4. Push .podspec file to origin
``` pod repo push PrivateRepoName Project.podspec ```
