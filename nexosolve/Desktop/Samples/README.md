# NexoSolve samples

Put reviewed `.gh` or `.ghx` files directly in this folder. No samples are included yet.

Publish embeds these files in the GHA and includes the same folder in the Desktop package. No separate download service is needed. Bump the coordinated GHA/Desktop version when changing official samples.

In Grasshopper, add **NexoSolve > Help > NexoSolve Samples**, then click **Browse samples**. The list is refreshed each time. The component also accepts a personal folder through its context menu.

Opening a sample creates a working copy under `Documents/NexoSolve/Sample Projects/`; save your changes there. Official installed sample files are managed release assets and can be replaced during updates. Do not store personal work in those folders. Samples can contain executable Grasshopper scripts: review files before distributing them. Include any required plugins and setup instructions in the file.
