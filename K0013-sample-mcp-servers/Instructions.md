# Instructions

1. Download and install Python 3.13 64-bit from [Windows Store](https://apps.microsoft.com/detail/9pnrbtzxmb4z) (suggested for Windows) or from the [Python](https://www.python.org/) website.
2. In the command prompt or terminal, install all the dependencies for Python (you may use `python` instead of `py`):
    - `py -m pip install fastmcp`
    - `py -m pip install requests`
    - `py -m pip install keyring`
3. Download and install [Claude Desktop](https://support.anthropic.com/en/articles/10065433-installing-claude-desktop).
4. Download and install [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/install-azure-cli-windows).
5. In the command prompt or terminal run `az login` to authenticate with the Azure CLI
    - Alternatively, provide a personal access token in your environment variables as `POWERBI_TOKEN`
6. Click to install the [.dxt file](https://www.anthropic.com/engineering/desktop-extensions) to set up the local connector in Claude Desktop.
    - Alternatively, in Claude Desktop settings, go to "Extensions" > "Advanced Settings" > "Install Extension..." and select the .dxt file
7. Test the server with a published Power BI Semantic Model that you have access to.

See here for a demonstration: https://www.youtube.com/watch?v=jDA3opqA0HI 


**See here for more information:**
    - Fabric model reader: https://github.com/data-goblin/fabric-model-reader-mcp/tree/main 
    - Fabric workspace reader: https://github.com/data-goblin/fabric-workspace-reader-mcp

**NOTE:** These files are provided as-is without warranties or guarantees for demonstration and educational purposes only. You are responsible for ensuring due dilligence and compliance or regulatory requirements.
