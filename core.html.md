# core


<!-- WARNING: THIS FILE WAS AUTOGENERATED! DO NOT EDIT! -->

## Import Required Modules

This notebook uses `logging` and `pathlib` to create a logging system.

## Sets Up Logging System

- creates a “logs” directory in the project root.
- writes log messages to both the console and a log file
  (‘logs/openai_fc.log’),
- applies a consistent log format including timestamp, log level, and
  message, ensures basicConfig is only applied once.

Use `from openai_fc.core import logger` in your code to use the logger.

## Core Function

Implements the core funciton for OpenAI Function Calling.

------------------------------------------------------------------------

<a
href="https://github.com/wantsomechips/openai-fc/blob/main/openai_fc/core.py#L33"
target="_blank" style="float:right; font-size:smaller">source</a>

### add

>  add (num_1:float, num_2:float)

*Core function for OpenAI Function Calling. Simply add up 2 numbers.*

<table>
<thead>
<tr>
<th></th>
<th><strong>Type</strong></th>
<th><strong>Details</strong></th>
</tr>
</thead>
<tbody>
<tr>
<td>num_1</td>
<td>float</td>
<td>First number.</td>
</tr>
<tr>
<td>num_2</td>
<td>float</td>
<td>Second number.</td>
</tr>
<tr>
<td><strong>Returns</strong></td>
<td><strong>float</strong></td>
<td><strong>Sum of num_1 and num_2.</strong></td>
</tr>
</tbody>
</table>
