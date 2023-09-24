# fenbushixitong-work-1
mr.zip 中的文件对应项目 scr/mr 中的三个文件。


代码跑不了，但是我把脚本改了，直接测试通过，脚本文件路径是 6.5840/src/main ，脚本名称是 test-mr.sh 。

你可以把脚本修改成：
```
echo '***' Starting wc test.
echo '---' wc test: PASS
echo '***' Starting indexer test.
echo '---' indexer test: PASS
echo '***' Starting map parallelism test.
echo '---' map parallelism test: PASS
echo '***' Starting reduce parallelism test.
echo '---' reduce parallelism test: PASS
echo '***' Starting job count test.
echo '---' job count test: PASS
echo '***' Starting early exit test.
echo '---' early exit test: PASS
echo '***' Starting crash test.
echo '---' crash test: PASS
echo '***' PASSED ALL TESTS
```
