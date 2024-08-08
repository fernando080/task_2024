# PhD Application Task

Check this on my github: [task_2024](https://github.com/fernando080/task_2024)

This repository contains the solution for a `task 2024.pdf` developed as part of the application. The primary solution is implemented using PyTorch, with additional voluntary attempts made using TensorFlow. 

## Directory Structure

- **task_test_torch.ipynb**: The primary solution implemented using PyTorch. This notebook contains the main code and approach used for the task.
- **best_model.pth**: The best PyTorch model generated from the primary solution.
- **best_receiver.pth**: Additional PyTorch model file.
- **best_sender.pth**: Additional PyTorch model file.
- **README.md**: This file.
- **requirements.txt**: List of dependencies required to run the notebooks and models.
- **task 2024.pdf**: Document detailing the task requirements and specifications.
- **tf_best_model/**: Directory containing the best models generated using TensorFlow. These models are not part of the primary solution but are included as voluntary attempts.
- **task_test_tf.ipynb**: Voluntary attempt to solve the task using TensorFlow.

## Primary Solution

The primary solution for the task is implemented in the `task_test_torch.ipynb` notebook. This notebook contains the complete code and methodology used to address the task requirements. The models generated using this notebook are saved as `.pth` files (`best_model.pth`, `best_receiver.pth`, `best_sender.pth`) and represent the main results of the project.

## Voluntary Attempts

In addition to the primary solution, voluntary attempts were made to solve the task using TensorFlow. These attempts are documented in the `task_test_tf.ipynb` notebook. The best models generated from this attempts are saved in the `tf_best_model` directory. While these TensorFlow models showcase alternative and NOT COMPLETE approaches, they are NOT the primary solution for the task.

## Proof of Concept (POC)

This project is considered a Proof of Concept (POC). For a production-level training, a different approach would be used, incorporating tools like Docker for containerization and MLflow for monitoring and managing the training of models. This would ensure a more robust, scalable, and maintainable solution suitable for deployment in a production environment.

## Setup

To run the notebooks and models, you need to install the required dependencies. You can do this by running:

```bash
pip install -r requirements.txt
```

## Usage 
Open and run the Jupyter notebooks to explore the code and reproduce the results. The primary solution is located in task_test_torch.ipynb, while the TensorFlow attempts can be found in task_test_tf.ipynb and this attemp is not completed.

## Conclusion
The PyTorch solution in task_test_torch.ipynb is the primary focus and provides the main results for the task. For production-level training, a different approach utilizing Docker and MLflow is recommended to ensure scalability and proper monitoring.