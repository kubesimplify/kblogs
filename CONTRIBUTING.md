# Contributing to Kubesimplify Blogs

Welcome to the **Kubesimplify Blogs Contributing Guide**. We are excited to have you showcase your learnings and journey with [Kubesimplify](https://kubesimplify.com/) and empower the Cloud-native ecosystem with us!

## Getting Started

To contribute to the KubeSimplify blog, please follow the steps below:

1. The very first step to get started would be to [open an issue](https://github.com/kubesimplify/kblogs/issues), so that we can understand your topic and ideas. **Once the idea gets accepted, you are all set to go!**

2. Fork the repository to your own account.

3. Clone the forked repository to your local machine:
    ```
   git clone https://github.com/your_username/kblogs
    ```
4. Create a new branch with a descriptive name for your contribution:
    ```
    git checkout -b add:<username-short_blog_keyword>
    ```
5. Make a new directory at the location - **`content/_posts/<year>/<month>`**. Please make sure the directory name follows the format **`YYYY-MM-DD-title-of-post`**:
    
    For example:
    ```
    mkdir -p content/_posts/2023/May/2023-05-20-Kubernetes-Security
    ```
6. To add your blog content, create an `index.md` file inside the created directory

    For example:
    ```
    touch content/_posts/2023/May/2023-05-20-Kubernetes-Security/index.md
    ```
7. Additionally, if your blog has images/visual diagrams, please upload those files separately to the same directory.

8. Add and Commit your changes to Git with a descriptive commit message:
    ```
    git add content/_posts/2023/May/2023-05-20-Kubernetes-Security
    git commit -m "add:blog_title"
    ```
9. Push your changes to your forked repository:
    ```
    git push origin main
    ```
10. Open a **pull request (PR)** from your branch to the **`main`** branch of the [kblogs](https://github.com/kubesimplify/kblogs) repository.

11. Once you make a **pull request (PR)**, please be patient as you'll be working with the reviewers for any necessary improvements.

## Guideline for Blog Posts

Please make sure to follow the guidelines and best practices mentioned in the [Style Guide](https://) while writing your blog post.

## Code of Conduct

Before contributing, please ensure that you have read and understood our **Code of Conduct** (At Kubesimplify, we strive to follow the [CNCF Code of Conduct](https://github.com/cncf/foundation/blob/main/code-of-conduct.md)).

## Conclusion

We appreciate your interest in contributing to Kubesimplify Blogs. By following the guidelines and best practices outlined in this document, you can help us maintain high-quality blogs with informative content. 

If you have any questions or feedback, please feel free to reach out to us at kubesimplify@gmail.com or **#kblogs** channel on our [discord community](https://discord.gg/QmsqabA2xT).