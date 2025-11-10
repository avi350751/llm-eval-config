Dataset generation
Your dataset is the heart of your LLM eval. To the extent possible, it should closely represent true inputs into your LLM app.

promptfoo can extend existing datasets and help make them more comprehensive and diverse using the promptfoo generate dataset command. This guide will walk you through the process of generating datasets using promptfoo.

Output format
# Interactive web viewer (default)
promptfoo eval

# Save as HTML report
promptfoo eval --output results.html

# Export as JSON for further processing
promptfoo eval --output results.json

# Create CSV for spreadsheet analysis
promptfoo eval --output results.csv

# Generate XML for integration with other tools
promptfoo eval --output results.xml
