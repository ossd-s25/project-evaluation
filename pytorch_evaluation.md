# Project Evaluation Activity



__Project Name:__  PyTorch


---

## Finding info about contributing on the website.

In the following section you should only enter the information that you
found on the project website. Some of the answers will be impossible to find, others
may be very hard to find. Do not _google_ for answers.

__Project website:__ [PyTorch](https://pytorch.org/)


__What is the purpose of the project:__ The project is for "tensor computation with strong GPU acceleration and deep neural networks built on a tape-based autograd system." In brief, it is a machine learning framework built for use in Python.


__How easy was it to find information about contributing on the website?__ The website is built with the primary purpose of providing information to users, but finding info on contributing just took a few clicks.

__Contributing instructions:__ [PyTorch Contribution Guide](https://pytorch.org/docs/stable/community/contribution_guide.html) 

__URL for the code repository:__ [PyTorch](https://github.com/pytorch/pytorch)

__Bug/Issue tracker link:__ [Bug/Issue tracker (GitHub)](https://github.com/pytorch/pytorch/issues)

__Mailing list:__ [Mailing list](https://twitter.us14.list-manage.com/subscribe?u=75419c71fe0a935e53dfa4a3f&id=91d0dccd39)

__Chat channel:__ [PyTorch Slack](https://pytorch.slack.com/)

__Other communication channels:__ [PyTorch Forums](https://discuss.pytorch.org/)


---

## Finding info at the project repository and bug/issue tracker.

__License:__ [License](https://github.com/pytorch/pytorch/blob/main/LICENSE)

__Is it [OSI approved](https://opensource.org/licenses/alphabetical) license:__ No. It seems to follow Open Source principles, but it doesn't seem to match any specific OSI license.

__Programming Language(s):__ Primarily Python and C++, with some Cuda, C, Objective-C++, and CMake

__URL for contributing instructions:__ [Contributing instructions](https://github.com/pytorch/pytorch/blob/main/CONTRIBUTING.md)

__Are the contributing instructions clear?__ The instructions are very detailed, but complex.


__URL for code of conduct / community norms / community guildelines:__ [Community Guidelines](https://github.com/pytorch/pytorch/blob/main/CODE_OF_CONDUCT.md)

__URL for instructions for users to download and install the package:__  [Contained in the README](https://github.com/pytorch/pytorch/blob/main/README.md#installation). 

__Are these instructions clear? Do you think they would be easy to follow?__ Yes, they are easy to follow. In fact, some members of our group have already installed and used it prior to this evaluation.

__URL for instructions for how to install development environment:__ [Contained in CONTRIBUTING](https://github.com/pytorch/pytorch/blob/main/CONTRIBUTING.md)

__Are these instruction clear? Do you think they would be easy to follow?__ Yes, they are very detailed and easy to follow.

__Number of contributors:__ 3,678 contributors

__Usernames of three contributors with largest number of commits; for
each of them list the link to their latest commit__:

1. [ezyang] (3,294 commits) - [Add nitpick warning that aoti_torch/c/shim.h is ABI stable (#145745)](https://github.com/pytorch/pytorch/commit/635b98fa087fa21acfdf35e95e0f2c2f56064605)
1. [pytorchmergebot] (3,042 commits) - [Revert "Add torch._scaled_mm for CPU (#139975)"](https://github.com/pytorch/pytorch/commit/babb2dc2afd8f9ace955df3e8773664ee6e438a7)
1. [malfet] (2,416 commits) - [[MPS][BE] Turn exec_unary_kernel as MetalShaderLibrary method (#147299)](https://github.com/pytorch/pytorch/commit/e8b20f6ef39e006e6da90de736ae85a1ba55c159)


__Number of commits:__ 84,546 commits

__Latest commit__ 

- __link to the commit:__ [[caffe2] disable warning for unused arguments (#147411)](https://github.com/pytorch/pytorch/commit/9fee408daa9573c387ccc0682562c91598b70deb)

- __who made that commit:__ rmaz

- __what type of work was commited?__ (It was a fix because it disabled warnings for unused arguments, which can be thought of as a bug of the library.)


__Issues__

- __how many open issues are there:__ [14,525 Open Issues](https://github.com/pytorch/pytorch/issues?q=is%3Aissue%20state%3Aopen%20)

    - __url for the last issue created:__ [Performance regression on modded-nanogpt torch-2.7.0.dev20250208→torch-2.7.0.dev20250209 #147463](https://github.com/pytorch/pytorch/issues/147463)

    - __how many users discuss the issue:__ 1 person
    
    - __when was the issue reported:__ Feb 19, 2025, 12:11 pm ET
    

- __how many closed issues are there:__ [34,438 closed issues](https://github.com/pytorch/pytorch/issues?q=is%3Aissue%20state%3Aclosed)
    - __url for the last issue closed:__ [[Triton upstream] [Inductor] [ROCm] LLVM failure in some gemm kernels #147377](https://github.com/pytorch/pytorch/issues/147377)
    - __how many users discussed the issue:__ 3 people
    - __when was the issue reported:__ Feb 18, 2025
    - __when was the issue closed:__ Feb 19, 2025, ~9 am ET

- __how active is the discussion on the issues:__ Many open issues have very little discussion, likely due to the sheer number of them. Closed issues tend to have ~5-10 comments, though.

    - __example of a lot of good discussion:__ [Unable to use XPU device on PyTorch 2.6 #147226](https://github.com/pytorch/pytorch/issues/147226)
    
    - __example of an issue that does not have much discussion:__ [Never ending compile #147327](https://github.com/pytorch/pytorch/issues/147327)



- __are there issues marked "good for newbies", "beginner" or some other indicators that imply that they are good for beginner contributors:__ Yes, there is an "easy" tag, but it is rarely used.

    - __how many of such issues are there?__ [6 easy issues](https://github.com/pytorch/pytorch/issues?q=is%3Aissue%20label%3Aeasy%20)
    
    - __look at a few of them, do they look beginner friendly?__ They look beginner friendly because they are all document-related issues, but the documentation can be complex and technical.



- __are there issues marked "documentation" or some other indicators that imply that they are documentation (user or developer specific):__ 

    - __how many of such issues are there?__ 
        - [73 "topic: docs" issues](https://github.com/pytorch/pytorch/issues?q=is%3Aissue%20label%3A%22topic%3A%20docs%22%20)
        - [1,769 "module: docs" issues](https://github.com/pytorch/pytorch/issues?q=is%3Aissue%20label%3A%22module%3A%20docs%22)
    
    - __look at a few of them, do you think you could submit a fix?__ Yes, some issues of them are related to fonts, formatting, or broken link. Some technical issues are trivial and can be solved with the knowledge we have. There are many that are more sophisticated, though.


__Pull requests__

- __how many open pull requests are there:__ 1,117 pull requests

    - __url for the last pull request created:__ [add the torch.float8_e8m0fnu dtype to PyTorch #147466](https://github.com/pytorch/pytorch/pull/147466)
    
    - __when was the last pull request made:__ May 6, 2021

    - __url for the oldest pull request created:__ [Deprecate torch.svd and change svd -> linalg_svd #57772](https://github.com/pytorch/pytorch/pull/57772)
    
    - __when was the oldest pull request made:__ Sep 2, 2016

- __how many closed pull requests are there:__ 

    - __url for the last pull request closed:__ [not for land: just testing #147467](https://github.com/pytorch/pytorch/pull/147467)
    
    - __how many users discussed the pull request:__ 1 users
    
    - __when was the pull request made:__ Feb 19, 2025, 1:09 pm ET
    
    - __when was the pull request closed:__ Feb 19, 2025, 1:11 pm ET
    

- __do maintainers respond quickly to pull requests when they are opened?__ Yes (to solvable issues).


## Development Environment 

Each member of your group should attempt to configure the development environemnt 
for this project. Complete the following for each member:

| Name | Operating system | Was the installation successful? (if not, explain what went wrong and what you did to try to remedy it) | How long did the whole process take? | 
|:--:|:--:|:--:|:--:|
| Jack Tinker | MacOS | Successful | ~6 minutes |
| Yufeng Xu | MacOS | Successful | ~9 minutes |
| Harry Yang | / | / | / |



---


## Summary assesment
__How friendly is this project for beginner contributors?__
This project seems challenging for a beginner contributor. This due to the technical machine learning background required for most contributions, and also due to the culture we observed in the community. While no one seems "mean", the culture doesn't seem very beginner friendly. All discussions are inundated with technical jargon, and the "easy" tag appears to be pretty much defunct. That being said, there is a very large community and a wealth of detailed documentation, so to someone interested in machine learning, it seems like a decent, if challenging, candidate.

__Do the maintainers respond helpfully to questions in issues?__
The maintainers give respectful responses, but they don't come off as especially friendly, and they are not speaking in beginner-friendly language. We rarely saw "thank you" used in issues and PRs.

__Are people friendly in the issues, discussion forum, and chat (for example, IRC or Slack)?__
In our experience, everyone seemed to be respectful, but very matter-of-fact about things. Nothing indicated to us a strong sense of community.

__Do pull requests get reviewed?__
Yes. There is a robust system that assigns teams of reviewers based on the topic of the PR.


__Do maintainers thank people for their contributions?__
Rarely.


__Are there special skills required to contribute to the project? If so, what are they?__
Yes. Most contributions would require knowledge of machine learning/neural networks.


__Are there any special hardware/software requirements to be able to contribute to the project? If so, what are they?__
One of PyTorch's main features is GPU hardware acceleration. Without a GPU-enabled machine, I imagine many GPU-related issues would be challenging to help fix.
