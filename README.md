📋 Overview
Legal Document Sentiment Analysis is an AI-powered tool designed to help legal professionals analyze documents for sentiment classification and risk assessment. Utilizing advanced NLP models, including RoBERTa and FinBERT, the application offers comprehensive analysis of legal texts to identify potential compliance issues, assess document sentiment, and generate risk reports.

✨ Features
🤖 Advanced AI Models: Utilizes RoBERTa and FinBERT for accurate sentiment analysis
📄 Single Document Analysis: Analyze individual legal documents with detailed insights
📊 Batch Processing: Process multiple documents simultaneously for comprehensive analysis
⚠️ Risk Assessment: Automated risk level classification (High/Medium/Low)
📈 Interactive Visualizations: Dynamic charts and graphs using Plotly
🎯 Confidence Scoring: Detailed confidence metrics for each analysis
📋 Comprehensive Reports: Generate detailed analysis summaries and recommendations
📱 User-Friendly Interface: Intuitive Gradio-based web interface
🔧 Installation
Prerequisites
Python 3.8 or higher
pip package manager
Internet connection for model downloads
Quick Installation
# Clone the repository
git clone https://github.com/yourusername/legal-sentiment-analysis.git
cd legal-sentiment-analysis

# Install required packages
pip install -r requirements.txt

# Run the application
python main.ipynb
Manual Installation
# Install individual packages
pip install gradio
pip install transformers
pip install torch
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install plotly
🚀 How to Use
Single Document Analysis
Launch the application by running python main.ipynb
Open your browser and navigate to the provided local URL (typically http://localhost:7860)
Go to the "Single Document Analysis" tab
Paste your legal document text in the input field
Click "Analyze Document" to get instant results
Review the sentiment, confidence scores, and risk assessment
Batch Document Analysis
Navigate to the "Batch Document Analysis" tab
Enter multiple documents separated by empty lines
Click "Analyze All Documents" for comprehensive batch processing
Review the summary statistics and detailed results table
Explore interactive visualizations for deeper insights
Sample Documents
Click "Load Sample Documents" to test the application with pre-loaded legal text examples
🖥️ Demo Screenshots
image

🚀 WorkFlow
image

🧠 How It Works
The Legal Document Sentiment Analysis tool employs a multi-model approach:

1. Text Preprocessing
Cleans and normalizes legal document text
Handles document length limitations (512 tokens max)
2. Sentiment Analysis Pipeline
Primary Model: RoBERTa (Twitter-based sentiment analysis)
Legal Model: FinBERT (Financial/Legal domain-specific analysis)
Fallback: BERT Multilingual model for enhanced coverage
3. Risk Assessment Algorithm
High Risk: Negative sentiment in both models with confidence > 80%
Medium Risk: Negative sentiment in one model or moderate confidence (60-80%)
Low Risk: Positive/neutral sentiment with acceptable confidence levels
4. Visualization Engine
Interactive charts using Plotly
Sentiment distribution pie charts
Risk level bar charts
Confidence score histograms
🛠️ Technical Details
Models Used
cardiffnlp/twitter-roberta-base-sentiment-latest: Primary sentiment analysis
ProsusAI/finbert: Legal and financial domain analysis
nlptown/bert-base-multilingual-uncased-sentiment: Fallback model
Key Components
LegalSentimentAnalyzer: Main analysis class
analyze_single_document(): Individual document processing
analyze_multiple_documents(): Batch processing functionality
create_visualizations(): Interactive chart generation
assess_risk(): Risk level calculation algorithm
📊 Output Examples
Individual Analysis Results
Primary Sentiment: Positive/Negative/Neutral classification
Confidence Score: Percentage confidence in sentiment prediction
Legal Sentiment: Domain-specific sentiment analysis
Legal Confidence: Confidence in legal sentiment prediction
Risk Level: High/Medium/Low risk assessment
Summary: Actionable insights and recommendations
Batch Analysis Results
Comprehensive Summary: Total documents analyzed, sentiment distribution
Risk Assessment: Breakdown of risk levels across all documents
Average Confidence: Overall confidence metrics
Detailed Results Table: Document-by-document analysis
Interactive Dashboard: Visual analytics with multiple chart types
📈 Future Improvements
 Integration with document management systems
 Custom model training for specific legal domains
 Export functionality (PDF, CSV, Word)
 API endpoints for integration
 Multi-language support expansion
 Advanced risk scoring algorithms
 Cloud deployment options
👥 Contributing
We welcome contributions from the legal and AI communities:

Fork the repository
Create a feature branch (git checkout -b feature/legal-enhancement)
Commit your changes (git commit -m 'Add legal document classifier')
Push to the branch (git push origin feature/legal-enhancement)
Open a Pull Request
📞 Contact
Feel free to reach out if you have questions, suggestions, or would like to contribute:

GitHub: https://github.com/ARI-create193/AI-Legal-Sentiment-Analyzer
Email: aryankaminwar@gmail.com
LinkedIn: https://www.linkedin.com/in/aryan-omprakash-kaminwar-ari-0b226328a/
🔒 Privacy
The Legal Document Sentiment Analysis tool:

Performs all analysis locally on your device
Does not collect or transmit user data
Does not share documents with any third parties
Requires only necessary permissions to function properly
🙏 Acknowledgments
Hugging Face: For providing the transformer models
Gradio Team: For the excellent web interface framework
Legal Community: For domain expertise and feedback
Open Source Contributors: For continuous improvements
