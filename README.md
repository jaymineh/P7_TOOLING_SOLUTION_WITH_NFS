# Project 7 - DevOps Tooling Website Solution

In this project, I implemented a tooling website solution using PHP and Apache. This solution has several stateless web servers, which share a common database & accesses the same files using NFS (Network File System) for shared file storage.

Though the NFS server was set up on a completely different machine, the web servers were configured to "see" it as a local file system where they can serve the same files.

![image](https://user-images.githubusercontent.com/91850543/191932916-05f014f5-c23c-438f-97b1-4dd0fb4d02cb.png)

Kindly check `project.md` for more information.
