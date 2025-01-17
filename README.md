<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Segmentation - AI-Powered Edge Detection Tool</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #121212; /* Dark background */
            color: #f0f0f0; /* Light text color */
        }
        header {
            background-color: #121212; /* Dark blue header */
            color: white;
            padding: 20px 10px;
            text-align: center;
        }
        section {
            padding: 20px;
            margin: 20px auto;
            background: #1e1e1e; /* Slightly lighter dark background */
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.2);
            max-width: 900px;
        }
        h1 {
            color:whitesmoke;
        }
        h2 {
            color: #64b5f6; /* Light blue heading text */
        }
        code {
            background: #2e2e2e; /* Darker gray for code blocks */
            padding: 2px 4px;
            border-radius: 4px;
            color: #c3e88d; /* Greenish text for code */
        }
        pre {
            background: #2e2e2e; /* Darker gray for preformatted text */
            padding: 10px;
            border-radius: 4px;
            overflow-x: auto;
            color: #c3e88d;
        }
        ul, ol {
            margin: 10px 0;
            padding-left: 20px;
        }
        li {
            margin-bottom: 8px;
        }
        footer {
            text-align: center;
            margin: 20px 0;
            font-size: 0.9em;
            color: #b0bec5; /* Light gray for footer text */
        }
        a {
            color: #81d4fa; /* Light blue for links */
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

<header>
    <h1>Image Segmentation</h1>
    <p>AI-Powered Image Segmentation and Edge Detection Tool</p>
</header>

<section>
    <h2>✨ Features</h2>
    <ul>
        <li><strong>🖼️ Advanced Image Segmentation</strong>: Powered by <strong>K-Means clustering</strong>, ImageFusion divides images into distinct regions, highlighting important features for better visualization.</li>
        <li><strong>🔍 Precise Edge Detection</strong>: Leveraging the <strong>Canny Edge Detection</strong> algorithm, ImageFusion identifies sharp changes in pixel intensity, ensuring clean and accurate contours.</li>
        <li><strong>⚪ Accurate Circle Detection</strong>: The <strong>Hough Circle Transform</strong> detects circular shapes in images, making it ideal for applications involving round objects or patterns.</li>
        <li><strong>🎯 Contour Extraction</strong>: Seamlessly draws external contours to highlight distinct boundaries within the image.</li>
        <li><strong>⚡ Fast and Intuitive</strong>: Optimized for speed without compromising on results, ImageFusion ensures minimal processing time for real-time tasks.</li>
    </ul>
</section>

<section>
    <h2>🎯 Use Cases</h2>
    <ul>
        <li><strong>Computer Vision Applications</strong>: Detect and analyze key image features for tasks like object recognition or quality control in automated systems.</li>
        <li><strong>Graphic Design</strong>: Enhance visual elements by segmenting regions and isolating contours for creative projects.</li>
        <li><strong>Data Analysis</strong>: Simplify and preprocess complex images for use in machine learning and data visualization tasks.</li>
        <li><strong>Medical Imaging</strong>: Identify key regions in X-rays, MRIs, or other scans for diagnostic purposes.</li>
    </ul>
</section>

<section>
    <h2>💻 Technology Stack</h2>
    <ul>
        <li><strong>Python</strong>: Core programming language for seamless integration of algorithms.</li>
        <li><strong>OpenCV (cv2)</strong>: For advanced image processing techniques, including segmentation and edge detection.</li>
        <li><strong>NumPy</strong>: For efficient array manipulations during clustering and filtering processes.</li>
        <li><strong>Matplotlib</strong>: For visualizing results in an easy-to-understand manner.</li>
    </ul>
</section>

<section>
    <h2>🛠️ How to Use</h2>
    <ol>
        <li><strong>Install Required Libraries</strong>:  
            Install dependencies using pip:
            <pre><code>pip install opencv-python numpy matplotlib</code></pre>
        </li>
        <li><strong>Run the Script</strong>:  
            Place your image in the same directory as <code>main.py</code> and execute the script:
            <pre><code>python main.py</code></pre>
        </li>
        <li><strong>View Results</strong>:  
            <ul>
                <li><strong>Original Image</strong>: Displays the input image.</li>
                <li><strong>Segmented Image</strong>: Shows the regions segmented by K-Means clustering.</li>
                <li><strong>Edge Detection</strong>: Highlights detected edges and circles.</li>
            </ul>
        </li>
    </ol>
</section>

<section>
    <h2>✨ Example Outputs</h2>
    <h3>Original Image</h3>
    <p>The raw input image loaded into the script.</p>
    <h3>Segmented Image</h3>
    <p>Regions divided into distinct clusters for better feature visualization.</p>
    <h3>Edge and Contour Detection</h3>
    <p>Canny Edge Detection output with contours and circles superimposed.</p>
</section>

<footer>
    <p>ImageFusion transforms images into meaningful visual insights with speed and precision, empowering users to unlock the full potential of image processing!</p>
</footer>

</body>
</html>
