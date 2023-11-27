```python
!pip install dash
```

    Collecting dash
      Obtaining dependency information for dash from https://files.pythonhosted.org/packages/00/69/d0ee9c6524678e98d336464d5c898182794c6b2ba1e5507bc7010a126ce2/dash-2.14.1-py3-none-any.whl.metadata
      Downloading dash-2.14.1-py3-none-any.whl.metadata (11 kB)
    Collecting Flask<3.1,>=1.0.4 (from dash)
      Obtaining dependency information for Flask<3.1,>=1.0.4 from https://files.pythonhosted.org/packages/36/42/015c23096649b908c809c69388a805a571a3bea44362fe87e33fc3afa01f/flask-3.0.0-py3-none-any.whl.metadata
      Downloading flask-3.0.0-py3-none-any.whl.metadata (3.6 kB)
    Collecting Werkzeug<3.1 (from dash)
      Obtaining dependency information for Werkzeug<3.1 from https://files.pythonhosted.org/packages/c3/fc/254c3e9b5feb89ff5b9076a23218dafbc99c96ac5941e900b71206e6313b/werkzeug-3.0.1-py3-none-any.whl.metadata
      Downloading werkzeug-3.0.1-py3-none-any.whl.metadata (4.1 kB)
    Requirement already satisfied: plotly>=5.0.0 in c:\programdata\miniconda3\lib\site-packages (from dash) (5.18.0)
    Collecting dash-html-components==2.0.0 (from dash)
      Downloading dash_html_components-2.0.0-py3-none-any.whl (4.1 kB)
    Collecting dash-core-components==2.0.0 (from dash)
      Downloading dash_core_components-2.0.0-py3-none-any.whl (3.8 kB)
    Collecting dash-table==5.0.0 (from dash)
      Downloading dash_table-5.0.0-py3-none-any.whl (3.9 kB)
    Requirement already satisfied: typing-extensions>=4.1.1 in c:\programdata\miniconda3\lib\site-packages (from dash) (4.7.1)
    Requirement already satisfied: requests in c:\programdata\miniconda3\lib\site-packages (from dash) (2.31.0)
    Collecting retrying (from dash)
      Downloading retrying-1.3.4-py3-none-any.whl (11 kB)
    Collecting ansi2html (from dash)
      Downloading ansi2html-1.8.0-py3-none-any.whl (16 kB)
    Requirement already satisfied: nest-asyncio in c:\programdata\miniconda3\lib\site-packages (from dash) (1.5.6)
    Requirement already satisfied: setuptools in c:\programdata\miniconda3\lib\site-packages (from dash) (68.0.0)
    Requirement already satisfied: importlib-metadata in c:\programdata\miniconda3\lib\site-packages (from dash) (6.8.0)
    Requirement already satisfied: Jinja2>=3.1.2 in c:\programdata\miniconda3\lib\site-packages (from Flask<3.1,>=1.0.4->dash) (3.1.2)
    Collecting itsdangerous>=2.1.2 (from Flask<3.1,>=1.0.4->dash)
      Downloading itsdangerous-2.1.2-py3-none-any.whl (15 kB)
    Requirement already satisfied: click>=8.1.3 in c:\programdata\miniconda3\lib\site-packages (from Flask<3.1,>=1.0.4->dash) (8.1.7)
    Collecting blinker>=1.6.2 (from Flask<3.1,>=1.0.4->dash)
      Obtaining dependency information for blinker>=1.6.2 from https://files.pythonhosted.org/packages/fa/2a/7f3714cbc6356a0efec525ce7a0613d581072ed6eb53eb7b9754f33db807/blinker-1.7.0-py3-none-any.whl.metadata
      Downloading blinker-1.7.0-py3-none-any.whl.metadata (1.9 kB)
    Requirement already satisfied: tenacity>=6.2.0 in c:\programdata\miniconda3\lib\site-packages (from plotly>=5.0.0->dash) (8.2.3)
    Requirement already satisfied: packaging in c:\programdata\miniconda3\lib\site-packages (from plotly>=5.0.0->dash) (23.1)
    Requirement already satisfied: MarkupSafe>=2.1.1 in c:\programdata\miniconda3\lib\site-packages (from Werkzeug<3.1->dash) (2.1.1)
    Requirement already satisfied: zipp>=0.5 in c:\programdata\miniconda3\lib\site-packages (from importlib-metadata->dash) (3.17.0)
    Requirement already satisfied: charset-normalizer<4,>=2 in c:\programdata\miniconda3\lib\site-packages (from requests->dash) (2.0.4)
    Requirement already satisfied: idna<4,>=2.5 in c:\programdata\miniconda3\lib\site-packages (from requests->dash) (3.4)
    Requirement already satisfied: urllib3<3,>=1.21.1 in c:\programdata\miniconda3\lib\site-packages (from requests->dash) (1.26.18)
    Requirement already satisfied: certifi>=2017.4.17 in c:\programdata\miniconda3\lib\site-packages (from requests->dash) (2023.7.22)
    Requirement already satisfied: six>=1.7.0 in c:\programdata\miniconda3\lib\site-packages (from retrying->dash) (1.16.0)
    Requirement already satisfied: colorama in c:\programdata\miniconda3\lib\site-packages (from click>=8.1.3->Flask<3.1,>=1.0.4->dash) (0.4.6)
    Downloading dash-2.14.1-py3-none-any.whl (10.4 MB)
       ---------------------------------------- 0.0/10.4 MB ? eta -:--:--
       -- ------------------------------------- 0.6/10.4 MB 19.5 MB/s eta 0:00:01
       ------ --------------------------------- 1.6/10.4 MB 17.0 MB/s eta 0:00:01
       ------------ --------------------------- 3.1/10.4 MB 22.2 MB/s eta 0:00:01
       ----------------- ---------------------- 4.6/10.4 MB 26.7 MB/s eta 0:00:01
       ----------------------- ---------------- 6.1/10.4 MB 27.8 MB/s eta 0:00:01
       --------------------------------- ------ 8.6/10.4 MB 32.5 MB/s eta 0:00:01
       ---------------------------------------  10.4/10.4 MB 34.4 MB/s eta 0:00:01
       ---------------------------------------- 10.4/10.4 MB 32.7 MB/s eta 0:00:00
    Downloading flask-3.0.0-py3-none-any.whl (99 kB)
       ---------------------------------------- 0.0/99.7 kB ? eta -:--:--
       ---------------------------------------- 99.7/99.7 kB 5.6 MB/s eta 0:00:00
    Downloading werkzeug-3.0.1-py3-none-any.whl (226 kB)
       ---------------------------------------- 0.0/226.7 kB ? eta -:--:--
       --------------------------------------- 226.7/226.7 kB 13.5 MB/s eta 0:00:00
    Downloading blinker-1.7.0-py3-none-any.whl (13 kB)
    Installing collected packages: dash-table, dash-html-components, dash-core-components, Werkzeug, retrying, itsdangerous, blinker, ansi2html, Flask, dash
    Successfully installed Flask-3.0.0 Werkzeug-3.0.1 ansi2html-1.8.0 blinker-1.7.0 dash-2.14.1 dash-core-components-2.0.0 dash-html-components-2.0.0 dash-table-5.0.0 itsdangerous-2.1.2 retrying-1.3.4
    


```python
import dash
import dash_html_components as html
import plotly.graph_objects as go
import plotly.express as px
from dash import Dash, dcc, html, Output, Input, State, callback, no_update
import dash_core_components as dcc
import pandas as pd
import json

app = dash.Dash()

df = pd.read_csv('estrategis-ec.com_data_dash_data.csv',delimiter =";")

def fig_map(df):
    fig = px.scatter_mapbox(df, lat="lat", lon="lon",
                            height=600, width=900,
                            color="Empresas", size="Empresas", size_max=75, animation_frame='year',
                            color_continuous_scale='viridis',
                            mapbox_style="carto-positron", zoom=5.5, hover_name="City",
                            center={"lat": -2, "lon": -79.01})

    return fig

app.layout = html.Div([

    html.Div([
        dcc.Graph(id='map_plot1', figure=fig_map(df))],
        style={'width': '75%', 'display': 'inline-block'}),

    html.Div(style={'width': '25%', 'display': 'inline-block'}, id='my-graph-container')
])


##calback
@callback(
    Output(component_id='my-graph-container', component_property='children'),
    Input(component_id='map_plot1', component_property='clickData'))
def update_graph(clickData):
    if clickData:
        city = clickData['points'][0]['hovertext']
        print(city)

        dff = df[df['City'] == city]
        print(dff.head())
        fig1 = px.line(dff, x='year', y='Empresas', title=city)
        return dcc.Graph(figure=fig1)
    else:
        no_update


if __name__ == '__main__':
    app.run_server(debug=True, use_reloader=False, port=8059)
```

    C:\Users\o002089\AppData\Local\Temp\ipykernel_10464\3769928735.py:2: UserWarning: 
    The dash_html_components package is deprecated. Please replace
    `import dash_html_components as html` with `from dash import html`
      import dash_html_components as html
    C:\Users\o002089\AppData\Local\Temp\ipykernel_10464\3769928735.py:6: UserWarning: 
    The dash_core_components package is deprecated. Please replace
    `import dash_core_components as dcc` with `from dash import dcc`
      import dash_core_components as dcc
    



<iframe
    width="100%"
    height="650"
    src="http://127.0.0.1:8059/"
    frameborder="0"
    allowfullscreen

></iframe>




```python

```
