<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lung Cancer Detection Project</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Lung Cancer Detection using CNNs</h1>
        <p>
            <ul>Abaham Dit Manyang, Mangar Makur Machiek, Monica Ayen Bol</ul>
            <ul>Sapano Makuei Meen, Ngor Wek Wek</ul>
            University of Juba, South Sudan- Juba
        </p>
    </header>

    <nav>
        <ul>
            <li><a href="#overview">Overview</a></li>
            <li><a href="#dataset">Dataset</a></li>
            <li><a href="#model">Model</a></li>
            <li><a href="#results">Results</a></li>
            <li><a href="#code">Code</a></li>
        </ul>
    </nav>

    <main>
        <section id="overview">
            <h2>Project Overview</h2>
            <p>This project presents a system for the automated detection of lung cancer using Convolutional Neural Networks (CNNs). The goal is to classify medical images of the lungs into Normal, Benign, and Malignant categories, aiming to assist in early diagnosis and improve patient outcomes.</p>
            <p>Lung cancer is a significant health challenge, and timely detection is crucial. This project explores the application of deep learning techniques to enhance the accuracy and efficiency of this critical medical task.</p>
        </section>

        <section id="dataset">
            <h2>Dataset</h2>
            <p>The system was developed and evaluated using a dataset of lung medical images. The dataset is stored in an HDF5 file and is divided into training and testing sets. It includes images and their corresponding labels for three classes: Normal, Benign, and Malignant.</p>
            <p>For more details on the dataset structure and loading process, please refer to the code repository.</p>
            <!-- Optional: You can include some sample images or data statistics here -->
        </section>

        <section id="model">
            <h2>Model Architecture</h2>
            <p>The core of the system is a custom-built Convolutional Neural Network (CNN). The model architecture consists of:</p>
            <ul>
                <li>Multiple convolutional and pooling layers for feature extraction.</li>
                <li>Dense (fully connected) layers for classification.</li>
                <li>Dropout for regularization.</li>
            </ul>
            <p>The model is trained to learn complex patterns in lung images to differentiate between normal tissue, benign nodules, and malignant tumors.</p>
            <!-- Optional: Include a diagram or description of your model architecture -->
        </section>

        <section id="results">
            <h2>Results</h2>
            <p>The model's performance was evaluated on the unseen test dataset. Key metrics include:</p>
            <ul>
                <li>Overall test accuracy.</li>
                <li>Confusion matrix detailing performance per class.</li>
            </ul>
            <p>Visualizations of the training progress (loss and accuracy plots) and sample predictions are available in the code repository.</p>
            <!-- Optional: Embed images of your results (plots, confusion matrix) -->
            <div class="result-plots">
                 <img src="loss_plot.png" alt="Loss Plot">
                 <img src="accuracy_plot.png" alt="Accuracy Plot">
                 <img src="confusion_matrix.png" alt="Confusion Matrix">
            </div>
        </section>

        <section id="code">
            <h2>Code</h2>
            <p>The full source code for this project is available on GitHub. The repository includes the data loading scripts, model definition, training process, evaluation, and visualization code.</p>
            <p>You can find the repository here: <a href="YOUR_GITHUB_REPO_LINK" target="_blank">Link to GitHub Repository</a></p>
            <p>Instructions on how to run the code and reproduce the results are provided in the repository's README file.</p>
        </section>
    </main>

    <footer>
        <p>&copy; 2023 Your Name/Institution. All rights reserved.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
