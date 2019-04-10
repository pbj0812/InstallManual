# Ubuntu에 torch 설치
> 참고링크 : <http://www.kwangsiklee.com/2018/08/ubuntu에서-torch-설치하기/>
<pre><code>git clone https://github.com/torch/distro
cd distro
export TORCH_NVCC_FLAGS="-D__CUDA_NO_HALF_OPERATORS__"
bash install-deps
./install.sh
</code></pre>

