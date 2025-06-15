# Medicine Recommendation System

A Machine Learning-powered web application that provides personalized medical recommendations based on symptoms. The system uses a Support Vector Classification (SVC) model to predict possible conditions and provides relevant medications, precautions, dietary advice, and exercise recommendations.

⚠️ **Disclaimer**: This system is for educational and informational purposes only. It should not be used as a substitute for professional medical advice, diagnosis, or treatment. Always seek the advice of your physician or other qualified health provider with any questions you may have regarding a medical condition.

## Features 🌟

- Disease prediction based on symptoms using Machine Learning (SVM)
- Multiple symptom selection with user-friendly interface
- Personalized recommendations including:
  - Medications
  - Diet plans
  - Exercise recommendations
  - Precautionary measures
- Detailed disease descriptions
- Mobile-responsive design

## Tech Stack 💻

- **Backend**: Python, Flask
- **Frontend**: HTML, Bootstrap 5, JavaScript
- **Machine Learning**: scikit-learn (SVM classifier)
- **Data Processing**: pandas, numpy
- **Database**: CSV files for storing disease, symptom, and recommendation data

## Installation 🔧

1. Clone the repository:
```bash
git clone https://github.com/yourusername/Medicine-Recommendation-System.git
cd Medicine-Recommendation-System
```

2. Create a virtual environment (recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install the required packages:
```bash
pip install -r requirements.txt
```

4. Run the application:
```bash
python main.py
```

5. Open your browser and navigate to `http://localhost:5000`

## Project Structure 📁

```
Medicine-Recommendation-System/
├── datasets/                  # Dataset files
│   ├── symtoms_df.csv        # Symptoms dataset
│   ├── precautions_df.csv    # Precautions dataset
│   ├── workout_df.csv        # Exercise recommendations
│   ├── description.csv       # Disease descriptions
│   ├── medications.csv       # Medication recommendations
│   └── diets.csv            # Diet recommendations
├── models/                   # ML model files
│   └── svc.pkl              # Trained SVM classifier
├── static/                   # Static files
│   └── img.png              # Logo and images
├── templates/               # HTML templates
│   ├── index.html          # Main page
│   ├── about.html          # About page
│   ├── blog.html           # Blog page
│   ├── contact.html        # Contact page
│   └── developer.html      # Developer info page
├── main.py                 # Main Flask application
└── requirements.txt        # Project dependencies
```

## How It Works 🔄

1. User selects multiple symptoms from the dropdown menu
2. The system processes these symptoms using the trained ML model
3. Based on the predicted disease, the system provides:
   - Disease description
   - Recommended medications
   - Diet suggestions
   - Exercise recommendations
   - Precautionary measures

## Dataset 📊

The system uses multiple datasets to provide comprehensive recommendations:
- Symptoms and diseases correlation data
- Disease descriptions
- Medication recommendations
- Diet suggestions
- Exercise recommendations
- Precautionary measures

## Contributing 🤝

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License 📝

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏

Special thanks to:
- The medical professionals who helped validate our recommendations
- The open-source community for providing valuable resources and libraries
- All contributors who helped improve this system

## Contact 📧

Your Project Link: https://github.com/yourusername/Medicine-Recommendation-System

## 🔒 Privacy and Security

- No user data is collected or stored
- All processing is done locally
- No external API calls or data sharing

## 🔄 Future Improvements

- Enhanced ML model accuracy
- Additional symptoms and conditions
- Integration with medical databases
- Mobile application development
- Multi-language support

---
Made with ❤️ for better healthcare accessibility


