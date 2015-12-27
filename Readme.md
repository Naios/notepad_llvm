
# LLVM IR Syntax Highlighting for Notepad++

Simple LLVM IR syntax highlighting specification for [Notepad++](https://notepad-plus-plus.org/).

`Notepad++` > `Define your own language...` > `Import` > `llvm_ir.xml`

<style type="text/css">
    span {
        font-family: 'Courier New';
        font-size: 10pt;
        color: #000000;
    }
    .sc0 {} .sc2 {
        font-weight: bold;
        color: #009B4E;
    }
    .sc3 {} .sc4 {
        font-weight: bold;
        color: #77442F;
    }
    .sc5 {
        font-weight: bold;
        color: #007575;
    }
    .sc6 {
        font-weight: bold;
        color: #0000FF;
    }
    .sc8 {
        font-weight: bold;
        color: #0080FF;
    }
    .sc12 {} .sc24 {}
</style>

<div style="float: left; white-space: pre; line-height: 1; background: #FFFFFF; "><span class="sc2">; Function Attrs: nounwind uwtable
</span><span class="sc6">define</span><span class="sc24"> </span><span class="sc4">i32</span><span class="sc24"> </span><span class="sc5">@main</span><span class="sc12">(</span><span class="sc4">i32</span><span class="sc24"> </span><span class="sc5">%argc</span><span class="sc12">,</span><span class="sc24"> </span><span class="sc4">i8</span><span class="sc12">**</span><span class="sc24"> </span><span class="sc5">%argv</span><span class="sc12">)</span><span class="sc24"> </span><span class="sc0">#0</span><span class="sc24"> </span><span class="sc0">{</span><span class="sc24">
</span><span class="sc0">entry</span><span class="sc12">:</span><span class="sc24">
  </span><span class="sc5">%retval</span><span class="sc24"> </span><span class="sc0">=</span><span class="sc24"> </span><span class="sc8">alloca</span><span class="sc24"> </span><span class="sc4">i32</span><span class="sc12">,</span><span class="sc24"> </span><span class="sc6">align</span><span class="sc24"> </span><span class="sc3">4</span><span class="sc24">
  </span><span class="sc5">%argv</span><span class="sc12">.</span><span class="sc0">addr</span><span class="sc24"> </span><span class="sc0">=</span><span class="sc24"> </span><span class="sc8">alloca</span><span class="sc24"> </span><span class="sc4">i8</span><span class="sc12">**,</span><span class="sc24"> </span><span class="sc6">align</span><span class="sc24"> </span><span class="sc3">8</span><span class="sc24">
  </span><span class="sc5">%argc</span><span class="sc12">.</span><span class="sc0">addr</span><span class="sc24"> </span><span class="sc0">=</span><span class="sc24"> </span><span class="sc8">alloca</span><span class="sc24"> </span><span class="sc4">i32</span><span class="sc12">,</span><span class="sc24"> </span><span class="sc6">align</span><span class="sc24"> </span><span class="sc3">4</span><span class="sc24">
  </span><span class="sc8">store</span><span class="sc24"> </span><span class="sc4">i32</span><span class="sc24"> </span><span class="sc3">0</span><span class="sc12">,</span><span class="sc24"> </span><span class="sc4">i32</span><span class="sc12">*</span><span class="sc24"> </span><span class="sc5">%retval</span><span class="sc12">,</span><span class="sc24"> </span><span class="sc6">align</span><span class="sc24"> </span><span class="sc3">4</span><span class="sc24">
  </span><span class="sc8">store</span><span class="sc24"> </span><span class="sc4">i8</span><span class="sc12">**</span><span class="sc24"> </span><span class="sc5">%argv</span><span class="sc12">,</span><span class="sc24"> </span><span class="sc4">i8</span><span class="sc12">***</span><span class="sc24"> </span><span class="sc5">%argv</span><span class="sc12">.</span><span class="sc0">addr</span><span class="sc12">,</span><span class="sc24"> </span><span class="sc6">align</span><span class="sc24"> </span><span class="sc3">8</span><span class="sc24">
  </span><span class="sc8">store</span><span class="sc24"> </span><span class="sc4">i32</span><span class="sc24"> </span><span class="sc5">%argc</span><span class="sc12">,</span><span class="sc24"> </span><span class="sc4">i32</span><span class="sc12">*</span><span class="sc24"> </span><span class="sc5">%argc</span><span class="sc12">.</span><span class="sc0">addr</span><span class="sc12">,</span><span class="sc24"> </span><span class="sc6">align</span><span class="sc24"> </span><span class="sc3">4</span><span class="sc24">
  </span><span class="sc8">ret</span><span class="sc24"> </span><span class="sc4">i32</span><span class="sc24"> </span><span class="sc3">0</span><span class="sc24">
</span><span class="sc0">}</span><span class="sc24">
</span>
</div>
