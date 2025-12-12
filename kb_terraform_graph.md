

### Using Terraform with Graphviz
You have the option to graph a terraform plan, apply, or the cicle using Graphviz (dot language). <br>

**To generate a graph:** <br>
<code> terraform graph </code>

<code> terraform graph [options]</code>
<br>

**Using options:**
- <code> -type=plan </code>
- <code> -type=apply </code>
- <code> -type=cicles </code>

#### Option 1:
<code> terraform graph | dot -Tpng > graph.png </code>

#### Option 2:
<code> terraform graph > tf_graph.dot </code>
<br>
<br>
<code> dot -Tpng  tf_graph.dot -o tf_graph.png </code>
<br>

