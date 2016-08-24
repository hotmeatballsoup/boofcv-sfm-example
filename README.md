# boofcv-sfm-example
Shows how to use BoofCV in **structure frpm motion** (Sfm) applications. Code is admittedly stolen right from their own `examples/` repo, but this shouldn't violate any licensing criteria (afterall, they're open source and this is just an API demo).

## Build & Run Locally

1. Clone this repo
2. Inside the `boofcv-sfm-example` parent directory, run: `./gradlew run`
3. BoofCV will now start inspecting all the images which you can find for yourself in `src/main/resources/images`. It will take about a minute for it to complete its processing (you'll see continuous console output the whole time)
4. BoofCV will then render its own 3D model (reconstruction) of the chair. You can kind of make it out with all the dots, but it will be blurry.
5. `open src/main/resources/images/chair006.jpg` to compare what BoofCV has rendered ("seen") vs. an actual photo of the chair
